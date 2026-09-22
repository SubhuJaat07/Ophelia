# 🔒 **Security & Privacy**

> *How Ophelia keeps your data and server safe*

---

## 📋 **Table of Contents**

1. [Security Overview](#security-overview)
2. [Authentication](#authentication)
3. [Data Protection](#data-protection)
4. [Privacy Policy](#privacy-policy)
5. [Infrastructure Security](#infrastructure-security)
6. [Responsible Disclosure](#responsible-disclosure)

---

## **Security Overview**

Ophelia implements industry-standard security practices to protect:

✅ **User Data** - Your information is encrypted and secure  
✅ **Server Safety** - Anti-nuke, anti-raid protections  
✅ **Dashboard** - Secure web interface with proper auth  
✅ **APIs** - Rate-limited, validated, protected  
✅ **Communication** - Encrypted connections only  

### **Security Metrics**
| Metric | Status |
|--------|--------|
| HTTPS Enforcement | ✅ Active |
| Authentication | ✅ OAuth2 + Sessions |
| CSRF Protection | ✅ Enabled |
| Rate Limiting | ✅ Configured |
| Input Validation | ✅ All endpoints |
| XSS Prevention | ✅ Output encoded |
| SQL Injection | ✅ Parameterized |
| Open Redirect | ✅ Blocked |

---

## **Authentication**

### **Discord OAuth2**
- Secure authentication via Discord's official system
- No password storage (uses Discord tokens)
- Scoped permissions (only what's needed)
- Token refresh automatically handled

### **Session Security**
- HttpOnly cookies (JavaScript cannot access)
- Secure flag (HTTPS only in production)
- SameSite=Lax (CSRF protection)
- Custom session name (not default)
- 24-hour session expiration
- Automatic invalidation on logout

### **Permission System**
- Discord permission checks before actions
- Role-based access control
- Granular permissions (no unnecessary access)
- Owner-only sensitive operations

---

## **Data Protection**

### **Input Sanitization**
All user inputs are:
- ✅ Validated (type, length, format)
- ✅ Sanitized (special characters escaped)
- ✅ Parameterized (SQL injection safe)
- ✅ Length-limited (buffer overflow prevention)

### **Output Encoding**
- HTML entities escaped in templates
- JSON properly serialized
- URLs validated before use
- User content never trusted

### **Sensitive Data Handling**
| Data Type | Protection |
|-----------|------------|
| Birthdays | Year/age hidden from public |
| User IDs | Always validated format |
| Session Tokens | Cryptographically secure |
| API Keys | Server-side only, never exposed |
| Auth Tokens | Short-lived, auto-expire |

### **Database Security**
- Supabase (PostgreSQL) with RLS
- No raw user queries
- Parameterized statements only
- Encrypted connections
- Regular backups

---

## **Privacy Policy**

### **Data We Collect**
| Data | Purpose | Retention |
|------|---------|-----------|
| User ID | Identity | While in server |
| XP/Levels | Game mechanics | Indefinite |
| Command Usage | Analytics | 30 days |
| Server Config | Functionality | While bot in server |
| Dashboard Session | Auth | 24 hours |

### **Data We DON'T Collect**
❌ Messages content (unless for specific features)  
❌ Private channel data  
❌ DM conversations  
❌ Passwords or credentials  
❌ Personal Identifiable Information (PII)  
❌ Payment information  

### **Your Rights**
- ✅ **Access** - Request your data
- ✅ **Deletion** - Delete your data
- ✅ **Export** - Download your data
- ✅ **Opt-out** - Disable features
- ✅ **Portability** - Take your data elsewhere

### **Third-Party Sharing**
We **never sell** your data to third parties. Limited sharing occurs only with:
- **Supabase** - Database hosting (encrypted)
- **Discord** - Authentication (OAuth2 only)
- **AI Providers** - Image generation (no PII sent)

All third parties have strict data protection agreements.

---

## **Infrastructure Security**

### **Network Security**
- HTTPS/TLS 1.3 encryption
- DDoS protection (via hosting provider)
- Firewall rules configured
- No open ports except necessary

### **Application Security**
```
┌─────────────────────────────────────┐
│         SECURITY LAYERS             │
├─────────────────────────────────────┤
│  1. HTTPS/TLS Encryption           │
│  2. Rate Limiting (per IP/user)     │
│  3. CSRF Token Validation          │
│  4. Session Authentication         │
│  5. Permission Checks              │
│  6. Input Validation               │
│  7. Output Encoding                │
│  8. SQL Injection Prevention       │
│  9. XSS Prevention                 │
│ 10. Open Redirect Blocking         │
└─────────────────────────────────────┘
```

### **Rate Limiting**
| Endpoint Type | Limit | Window |
|----------------|-------|--------|
| General API | 100 req/min | Per IP |
| Sensitive APIs | 10 req/min | Per IP |
| DM Features | 5 req/min | Per user |
| Auth Endpoints | 10 req/min | Per IP |
| Socket Events | 100 events/min | Per connection |

### **Anti-Abuse Systems**
- **Raid Detection** - Mass-join protection
- **Spam Filter** - Rapid message detection
- **Scam Blocker** - Known malicious links
- **Rate Limiter** - Prevent API abuse
- **Captcha** - Optional verification

---

## **Dashboard Security**

The web dashboard at [queen-ophelia.duckdns.org](https://queen-ophelia.duckdns.org/) includes:

### **Authentication Flow**
```
User clicks "Login with Discord"
    ↓
Redirect to Discord OAuth2
    ↓
User authorizes
    ↓
Receive secure token
    ↓
Create encrypted session
    ↓
Access dashboard
```

### **Protected Routes**
- All state-changing routes require CSRF token
- Session validation on every request
- Permission checks for server management
- Rate limiting on all API calls

### **Socket.IO Security**
- Session-based authentication (not client-controlled)
- Event-level permission checks
- Real-time abuse monitoring
- Connection rate limiting

---

## **Responsible Disclosure**

### **Found a Security Issue?**

We take security seriously! If you discover a vulnerability:

**DO:**
- ✅ Report it privately to us
- ✅ Provide reproduction steps
- ✅ Allow reasonable time to fix
- ✅ Keep details confidential until fixed

**DON'T:**
- ❌ Publicly disclose before fix
- ❌ Access/modify other users' data
- ❌ Disrupt service or availability
- ❌ Use exploits for personal gain

### **Report To**
- **Discord:** [Support Server](https://discord.gg/BD9Xx48WZd) (DM owners)
- **Response Time:** Within 48 hours
- **Bounty:** Recognition + special roles (case-by-case)

### **What We'll Do**
1. Acknowledge receipt within 24 hours
2. Investigate and reproduce issue
3. Deploy fix (typically within 1 week)
4. Credit you (if desired)
5. Possibly offer bounty/rewards

---

## **Security Changelog**

### **Recent Updates**
- **v3.0.0** (Sept 2026)
  - Enhanced session verification
  - Improved CSRF protection
  - Socket.io authentication hardening
  - Open redirect prevention
  - XSS protection improvements
  - PII data masking

- **v2.5.0** (Aug 2026)
  - Rate limiting improvements
  - Input validation enhancements
  - Dashboard security updates

---

## **Compliance**

### **Standards We Follow**
- 🔒 **GDPR** - European data protection
- 🛡️ **CCPA** - California privacy rights
- 📋 **COPPA** - Children's privacy (under 13 not targeted)
- 🌐 **Discord ToS** - Platform compliance

### **Data Residency**
- Primary: EU servers (GDPR compliant)
- Backup: US East coast
- All data encrypted at rest and in transit

---

## **Questions?**

If you have security or privacy concerns:

1. **Check this document** - Answer might be here
2. **Join Support Server** - [discord.gg/BD9Xx48WZd](https://discord.gg/BD9Xx48WZd)
3. **DM Owners** - Private discussion available
4. **Email** - (available in support server)

---

*Last Updated: September 2026*  
*Next Review: December 2026*

---

🔒 **Your security is our priority.** We continuously improve our security measures and appreciate community help in keeping Ophelia safe!
