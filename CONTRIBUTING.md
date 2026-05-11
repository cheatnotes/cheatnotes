# Contributing to Cheat Notes

Thank you for helping improve the **Cheat Notes For Dummies** organization! We welcome contributions to make our cheat sheets more comprehensive, accurate, and useful for everyone.

## About This Repository

This repository contains **ONE comprehensive cheat sheet** written entirely in the `README.md` file. All contributions focus on improving and expanding this single reference document.

## Table of Contents

- [What We Accept](#what-we-accept)
- [What We Don't Accept](#what-we-dont-accept)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Quality Standards](#quality-standards)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Markdown Style Guide](#markdown-style-guide)
- [Community](#community)

## What We Accept

### ✅ Contributions We Welcome

- **New sections** covering uncovered topics
- **Expanded examples** with better explanations
- **Corrected information** with updated links
- **Improved formatting** and readability
- **Better organization** and structure
- **Added references** and source links
- **Clarifications** of complex concepts
- **Practical use cases** and real-world examples
- **Translations** to other languages (in separate files)
- **Typo fixes** and grammar improvements

### Example Contributions

```markdown
# Before
- Command syntax example

# After
- Command syntax with clear explanation
- Real-world usage example
- Expected output
- Common mistakes to avoid
- Link to official documentation
```

## What We Don't Accept

### ❌ We Cannot Merge

- **External files** (this is a single README cheat sheet)
- **Executable code/scripts** (reference only, not runnable)
- **Duplicate content** (avoid repeating sections)
- **Advertising/promotion** (no spam or self-promotion)
- **Opinions** (stick to facts and best practices)
- **Unverified information** (test code, verify claims)
- **Malicious content** (exploits, hacks, harmful code)
- **Copyrighted material** (without proper attribution)
- **Off-topic content** (stay within cheat sheet scope)
- **Broken links** (verify all URLs work)

## Getting Started

### Prerequisites

- GitHub account
- Basic Git knowledge
- Markdown familiarity
- Understanding of the topic (for substantial contributions)

### Setup

1. **Fork the repository**
   ```bash
   # Click "Fork" on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
   cd REPO_NAME
   ```

3. **Add upstream remote**
   ```bash
   git remote add upstream https://github.com/cheatnotes/REPO_NAME.git
   ```

4. **Create a branch**
   ```bash
   git checkout -b improve/add-description
   ```

## How to Contribute

### Step 1: Identify the Gap

Review the current `README.md` and identify:
- Missing topics or sections
- Incorrect information
- Outdated examples
- Unclear explanations
- Broken links
- Poor organization

### Step 2: Research & Verify

Before contributing:
- ✅ Test all code examples
- ✅ Verify facts from multiple sources
- ✅ Check links work correctly
- ✅ Review official documentation
- ✅ Ensure information is current
- ✅ Compare with existing content

### Step 3: Make Improvements

Edit the `README.md` file:

```bash
# Edit the file
nano README.md

# Or use your preferred editor
vim README.md
# or
code README.md
```

### Step 4: Commit Changes

```bash
git add README.md
git commit -m "improve: add advanced SQL query examples"
```

**Commit message format:**
```
<type>: <short-description>

Optional longer description explaining the change.
```

### Step 5: Push & Create Pull Request

```bash
git push origin improve/add-description
```

Then create a **Pull Request** on GitHub with:
- Clear title
- Description of changes
- Why this improves the cheat sheet
- Links to reference material

## Quality Standards

### Content Quality Checklist

- [ ] Information is accurate and verified
- [ ] Examples are tested and work correctly
- [ ] Code follows best practices
- [ ] Language is clear and concise
- [ ] No typos or grammar errors
- [ ] Formatting is consistent
- [ ] All links work and are relevant
- [ ] Sources are credited
- [ ] No duplicate content
- [ ] No sensitive information (keys, passwords)

### Technical Accuracy

- Test all code examples before submitting
- Verify command syntax with official docs
- Run commands in your environment
- Include expected output if applicable
- Note version requirements (if any)

### Clarity Standards

- Use simple, direct language
- Avoid jargon (or explain it)
- Include practical examples
- Show common mistakes
- Provide working solutions
- Link to deeper resources

## Commit Guidelines

### Commit Message Format

```
<type>: <subject>

<body>
```

### Types

- `feat:` - New section or major addition
- `improve:` - Enhancement to existing content
- `fix:` - Correction of errors or mistakes
- `docs:` - Documentation improvements
- `refactor:` - Reorganization or restructuring
- `style:` - Formatting or style changes

### Examples

```
improve: expand SQL JOIN examples with more use cases

- Add INNER JOIN example
- Add OUTER JOIN comparison
- Add CROSS JOIN explanation
- Include performance notes

Fixes #42
```

## Pull Request Process

### Before Submitting

1. **Sync with upstream**
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Review your changes**
   - Read through all modifications
   - Check for clarity and accuracy
   - Verify links work
   - Test code examples

3. **Test in markdown viewer**
   - Preview on GitHub (if possible)
   - Check formatting renders correctly
   - Verify tables align properly
   - Ensure code blocks display correctly

### Submitting a PR

1. **Push your branch**
   ```bash
   git push origin improve/add-description
   ```

2. **Create Pull Request**
   - Use the PR template
   - Reference related issues
   - Explain what changed and why
   - Include any relevant context

3. **Complete the checklist**
   - [ ] Changes tested and verified
   - [ ] Formatting is consistent
   - [ ] All links work correctly
   - [ ] No duplicate content
   - [ ] Sources credited appropriately
   - [ ] Grammar and spelling checked
   - [ ] Commit message is clear

### Review Process

- Maintainers will review your PR
- They may request changes
- Approval requires 1-2 reviews
- Status checks must pass
- All comments must be resolved

### Responding to Feedback

- Check back regularly
- Respond to reviewer comments
- Make requested changes
- Push additional commits to same branch
- Re-request review when ready

## Markdown Style Guide

### Headings

```markdown
# Main Topic (H1)
## Major Section (H2)
### Subsection (H3)
#### Detail (H4)
```

### Code Blocks

**Syntax highlighting:**
```markdown
```language
code here
```
```

**Examples:**
```markdown
```sql
SELECT * FROM users;
```

```bash
ls -la
```

```python
print("Hello, World!")
```
```

### Lists

**Unordered:**
```markdown
- Item 1
- Item 2
  - Nested item
  - Another nested
- Item 3
```

**Ordered:**
```markdown
1. First step
2. Second step
3. Third step
```

### Tables

```markdown
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |
```

### Links

```markdown
[Link Text](https://example.com)
[Link with Title](https://example.com "Title")
```

### Emphasis

```markdown
**Bold text**
*Italic text*
~~Strikethrough~~
`Inline code`
```

### Inline Code vs Code Blocks

```markdown
Use `inline code` for short commands
Use code blocks for longer examples
```

## Content Organization

### Section Structure

```markdown
## Topic Name

Brief introduction (1-2 sentences)

### Subsection

Explanation and context

```
code example
```

**Key points:**
- Point 1
- Point 2

**Common mistakes:**
- Mistake 1
- Mistake 2

**Related topics:**
- [Link to related topic](#)
```

### Including Examples

```markdown
### Example: Description

```
command or code
```

**Explanation:** What this does...
**Output:** What you should see...
```

## Verification Checklist

Before final submission:


- [ ] Information verified against official sources
- [ ] All code examples tested
- [ ] Links checked and working
- [ ] Formatting consistent throughout
- [ ] No typos or grammar errors
- [ ] No duplicate content with existing sections
- [ ] Sources and references credited
- [ ] Markdown renders properly on GitHub
- [ ] Tables and lists display correctly
- [ ] No sensitive information included


## Getting Help

### Questions?

- **Discussions:** [GitHub Discussions](https://github.com/cheatnotes/cheatnotes/discussions)
- **Issues:** [Open an issue](https://github.com/cheatnotes/REPO/issues)
- **Documentation:** Read the [README](./README.md)
- **Main Org:** [@cheatnotes](https://github.com/cheatnotes)

### Helpful Resources

- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [Cheat Notes Organization](https://github.com/cheatnotes)
- [SQL Cheatsheet Example](https://github.com/cheatnotes/sql-cheatsheet)

## Recognition

Contributors are recognized:
- In the README commit history
- In GitHub contributors section
- In release notes (for major contributions)

## Code of Conduct

All contributors must follow our [Code of Conduct](./CODE_OF_CONDUCT.md). We maintain a respectful, inclusive environment.

## License

By contributing, you agree your contributions are licensed under the **MIT License**. All contributions become part of the open-source project.

---

**Thank you for improving Cheat Notes!** 🎉

Your contributions help thousands of developers learn faster.

*Last Updated: 2026-05-11*


