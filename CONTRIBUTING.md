# 🤝 Contributing to Ophelia Documentation

Thank you for your interest in improving Ophelia's public documentation! This repo contains **documentation only** - no bot source code.

---

## **How You Can Contribute**

### **1. 📝 Documentation Improvements**
- Fix typos or grammar errors
- Clarify confusing explanations
- Add missing command descriptions
- Improve examples or usage guides
- Translate documentation to other languages

### **2. 🖼️ Screenshots & Assets**
- Add dashboard screenshots (blur sensitive info)
- Create feature demonstration GIFs
- Design better icons or graphics
- Improve visual presentation

### **3. 🐛 Bug Reports**
- Documentation inaccuracies
- Broken links
- Outdated information
- Missing security updates

### **4. 💡 Feature Suggestions**
- New sections to add
- Better organization ideas
- User guide improvements
- FAQ additions

---

## **Getting Started**

### **Prerequisites**
- GitHub account
- Basic Markdown knowledge
- Text editor (VS Code recommended)
- Love for Discord bots! 😊

### **Setup Steps**

1. **Fork the Repository**
   ```bash
   # Click "Fork" button on GitHub
   # Then clone your fork:
   git clone https://github.com/YOUR_USERNAME/ophelia-bot-public.git
   cd ophelia-bot-public
   ```

2. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Edit files in your text editor
   - Follow the style guide below
   - Test markdown rendering

4. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "docs: add description for /meme command"
   ```

5. **Push and Create PR**
   ```bash
   git push origin feature/your-feature-name
   # Then create Pull Request on GitHub
   ```

---

## **Style Guide**

### **Markdown Format**
- Use **UTF-8** encoding
- Line length: ~100 characters max
- Use spaces for indentation (not tabs)
- One blank line between sections

### **Headings**
```markdown
# H1 - Main title (rarely use)
## H2 - Section headers
### H3 - Sub-sections
#### H4 - Detailed breakdowns
```

### **Code Blocks**
````markdown
**For commands:**
```text
/command <required> [optional]
```

**For JavaScript (if needed):**
```javascript
const example = 'hello';
```
````

### **Tables**
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data | More data | Even more |

### **Emojis**
- Use emojis sparingly (for section headers, not every line)
- Keep it professional but friendly
- Accessibility: Don't overuse

### **Links**
```markdown
[Text](url) - External links
[Text](./path) - Internal links
<url@> - Bare URLs (avoid when possible)
```

---

## **Documentation Structure**

```
ophelia-bot-public/
├── README.md              # Main page (Top.gg landing)
├── LICENSE               # MIT License
├── .gitignore            # Git ignore rules
└── docs/
    ├── FEATURES.md       # Complete features guide
    ├── SECURITY.md       # Security & privacy info
    └── DASHBOARD.md      # Dashboard tour guide
```

### **Where to Put Things**

| Content Type | Location |
|--------------|----------|
| Command descriptions | `README.md` or `FEATURES.md` |
| Security info | `docs/SECURITY.md` only |
| Dashboard pages | `docs/DASHBOARD.md` only |
| General improvements | `README.md` |
| Images/GIFs | `assets/` folder |

---

## **Pull Request Guidelines**

### **PR Title Format**
```
docs: brief description of change
```

**Examples:**
- `docs: fix typo in README installation section`
- `docs: add /imagine command examples`
- `docs: update dashboard screenshots`
- `docs: clarify security section`

### **PR Description Template**
```markdown
## Description
Brief explanation of what changed and why.

## Type of Change
- [ ] Bug fix (documentation error)
- [ ] New content (added section/info)
- [ ] Update (outdated info refreshed)
- [ ] Style (formatting, typos)

## Screenshots (if applicable)
[Add screenshots here]

## Checklist
- [ ] I've followed the style guide
- [ ] Links are working
- [ ] No sensitive data in screenshots
- [ ] Spelling and grammar checked
- [ ] I've tested markdown rendering
```

### **Review Process**
1. Maintainers will review within 48 hours
2. May request changes or clarifications
3. Once approved, will be merged
4. Your contribution will be credited! 🎉

---

## **What NOT to Include**

❌ **Never add to this repo:**
- Bot source code
- API keys or secrets
- Environment variables
- Internal architecture details
- Elite/Super owner commands or powers
- Sensitive configuration examples
- Personal user data
- Server IP addresses or internal URLs

✅ **Safe to include:**
- Public-facing command descriptions
- User-visible features
- Dashboard page layouts (general)
- Security best practices (general)
- Help text and examples
- Screenshots (blurred/anonymized)

---

## **Community Guidelines**

### **Be Respectful**
- Welcome newcomers
- Assume good intent
- Constructive feedback only

### **Quality Over Quantity**
- Better one great PR than five rushed ones
- Test your changes before submitting
- Proofread for errors

### **Ask Questions**
- If unsure, ask in an issue or discussion
- We're happy to help!
- No question is too basic

---

## **Recognition**

All contributors will be recognized:

- **GitHub Contributors** list on repo
- Special thanks in release notes
- Discord role (for significant contributions)
- Mention in community posts

---

## **Need Help?**

- **Issues:** [Create GitHub Issue](issues)
- **Discord:** [Support Server](https://discord.gg/BD9Xx48WZd)
- **Questions:** Start a [Discussion](discussions)

---

**Thank you for helping make Ophelia's documentation better!** 🎉

*Every contribution, no matter how small, helps the community!*
