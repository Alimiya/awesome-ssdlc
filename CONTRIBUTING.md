# Contributing to Awesome SSDLC

This guide helps you contribute to the **Secure Software Development 
Lifecycle** curated list of **SSDLC resources**, **security tools**, 
and **frameworks**.

## How to Contribute

1. Fork the repository
2. Create a feature branch: `git checkout -b add/resource-name`
3. Add your resource(s) following the guidelines below
4. Test your changes (run awesome-lint)
5. Submit a pull request with a clear description

## Guidelines

### What Makes a Good Resource?

**Include:**
- Active, well-maintained projects (updated in last 2 years)
- High-quality, authoritative sources
- OWASP, NIST, and vendor-neutral frameworks
- Free and commercial tools (if they offer free tiers)
- Practical, actionable content

**Exclude:**
- Outdated or abandoned projects
- Low-quality, spam, or promotional content
- Duplicate listings
- Broken links
- Vendor lock-in bias

### Writing Descriptions

**Format:**
```markdown
- [Resource Name](https://url) - Brief description (max 50 chars)
```

**Do:**
- Explain value: `[Tool](url) - SAST for JavaScript, Python, Java`
- Be concise: max 50 characters
- Be neutral: objective, no marketing language
- Be accurate: description matches the resource

**Don't:**
- Too vague: `[Tool](url) - Security (what does it do?)`
- Too long: `[Tool](url) - Advanced static analysis with machine learning-powered detection...`
- Marketing: `[Tool](url) - THE BEST security scanner for total protection!`
- No description: `[Tool](url)`

### Organization

Place your resource in the appropriate section and subsection:
- Phase 1: Planning & Requirements
- Phase 2: Design & Architecture
- Phase 3: Secure Coding & Development
- Phase 4: Security Testing & Verification
- Phase 5: Release & Deployment
- Phase 6: Operations & Monitoring
- Phase 7: Continuous Improvement
- Frameworks & Standards
- Tools by Category
- Language-Specific Resources
- Books & Papers
- Communities & Events

### Quality Checks

Before submitting, verify:

- [ ] Link is live and works (no 404s)
- [ ] Description is 50 chars or less
- [ ] Description matches the resource
- [ ] No spelling or grammar errors
- [ ] Resource is relevant to SSDLC
- [ ] Resource is not already listed
- [ ] Resource is actively maintained
- [ ] Formatting is consistent

### Running awesome-lint

```bash
# Install awesome-lint
npm install -g awesome-lint

# Check for issues
awesome-lint README.md

# Fix any errors before submitting PR
```

## Pull Request Process

1. **Title:** Be clear about what you're adding
   - Good: "Add Trivy container scanning tool"
   - Bad: "Update README"

2. **Description:** Explain why this resource is valuable
```markdown
   **Title:** Add Trivy container scanning tool

   **Why:** Fast, open-source vulnerability scanner for containers and IaC.
   Fits in Phase 5: Release & Deployment.

   Checklist:
   - [x] Passes awesome-lint
   - [x] Resource is actively maintained
   - [x] Description is accurate and concise
```

3. **Wait for review:** Maintainers will provide feedback

4. **Address feedback:** Update your PR as needed

5. **Get merged!**

## Quality Standards

### Content Quality

- No spam, low-quality, or abandoned projects
- Resources updated in last 2 years
- Clear, working links
- Accurate, neutral descriptions
- No duplicates

### README Quality

- Proper Markdown formatting
- Consistent link style: `[Name](url) - Description`
- Logical section organization
- Working table of contents
- No typos or grammar errors

### Code Quality

- awesome-lint passes
- All links 404-free
- Proper formatting
- Consistent style

## Maintenance

We maintain this list monthly by:
- Checking links (404 detection)
- Removing broken resources
- Reviewing community feedback
- Adding new high-quality resources
- Keeping descriptions current

## Questions?

- Open an issue to discuss
- Ask in pull request comments
- Check existing issues for answers

---

**Thank you for helping make awesome-ssdlc better!** 
