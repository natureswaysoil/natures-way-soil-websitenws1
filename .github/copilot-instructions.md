# Nature's Way Soil Website (natures-way-soil-websitenws1)

**CRITICAL**: Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.

## Repository Status: INITIAL SETUP REQUIRED

**CURRENT STATE**: This repository currently contains only a README.md file. The project requires initial setup to become a functional website for Nature's Way Soil business.

## Working Effectively

### Current Repository State
- Repository contains: README.md, .gitignore, .github/copilot-instructions.md
- No build system, dependencies, or application code exists yet  
- Technology stack has not been determined
- Issue #1 indicates need for a home page (website not yet implemented)

### Immediate Setup Requirements
Before any development can begin:

1. **Determine Technology Stack**:
   - Choose web framework (e.g., React, Vue, Angular, static site generator)
   - Decide on build tools and package manager
   - Select hosting/deployment strategy

2. **Initialize Project Structure**:
   - Create package.json or equivalent project file
   - Set up basic directory structure
   - Add .gitignore for chosen technology
   - Initialize build system

3. **Add Development Infrastructure**:
   - Configure linting and formatting tools
   - Set up testing framework
   - Create GitHub workflows for CI/CD

### Commands That Currently Work
```bash
# Repository exploration
ls -la                    # Shows: README.md, .gitignore, .git/, .github/
cat README.md            # Content: "# natures-way-soil-websitenws1"
cat .gitignore           # Shows files to ignore during development
git status               # Shows working tree status
git log --oneline        # Shows initial commit history
```

### Commands That Will Fail (Until Setup)
- `npm install` - No package.json exists (creates empty package-lock.json which is gitignored)
- `npm run build` - No build scripts configured  
- `npm test` - No test framework setup
- Any build/test/dev commands - No project initialized

## Technology-Specific Instructions (To Be Added)

### When Using Node.js/npm:
```bash
# Initialize project (AFTER technology decision)
npm init -y
npm install [dependencies]
npm run build            # NEVER CANCEL: Build time TBD. Set timeout 60+ minutes.
npm test                # NEVER CANCEL: Test time TBD. Set timeout 30+ minutes.
npm run dev             # Start development server
```

### When Using Python/Django:
```bash
# Initialize project (AFTER technology decision)
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### When Using Static Site Generator:
```bash
# Initialize project (AFTER technology decision)
# Commands will depend on chosen generator (Jekyll, Hugo, Gatsby, etc.)
```

## Validation Requirements

### Current Validation Steps
- Verify README.md exists and contains repository name
- Confirm repository structure matches expected minimal state
- Check that .github/copilot-instructions.md exists

### Future Validation Steps (After Setup)
- **MANUAL VALIDATION REQUIREMENT**: After building and running the application, test actual functionality by navigating through the website
- Verify home page loads and displays Nature's Way Soil branding
- Test responsive design on different screen sizes
- Validate all navigation links work correctly
- Ensure contact forms or business information is accessible

## Common Tasks

### Current Repository Inventory
```
Repository Root:
.
├── .git/
├── .github/
│   └── copilot-instructions.md
├── .gitignore
└── README.md
```

### README.md Contents
```
# natures-way-soil-websitenws1
```

## Build and Deployment (To Be Determined)

### Expected Build Process (Placeholder)
- Build time: TBD (NEVER CANCEL: Set timeout 60+ minutes)
- Test time: TBD (NEVER CANCEL: Set timeout 30+ minutes) 
- Deployment: TBD

### Pre-commit Requirements (To Be Added)
- Linting: TBD
- Testing: TBD
- Build verification: TBD

## Key Project Information

### Business Context
- **Business**: Nature's Way Soil
- **Project Type**: Business website
- **Known Issues**: 
  - Issue #1: No home page exists (requires full website implementation)
  - Issue #3: Setup Copilot instructions (this file)

### Repository Structure (Future)
- Will need home page implementation
- Should include business information, services, contact details
- May need product catalog, testimonials, contact forms

## Next Steps for Contributors

1. **Project Setup Decision Required**: Choose technology stack for the website
2. **Initialize Project**: Set up chosen framework with proper build tools
3. **Create Basic Website**: Implement home page to resolve Issue #1
4. **Update These Instructions**: Add specific build, test, and deployment commands once technology is chosen
5. **Add CI/CD**: Create GitHub workflows for automated building and deployment

## Important Notes

- **NEVER CANCEL BUILDS**: Once project is set up, builds may take significant time
- **UPDATE INSTRUCTIONS**: Modify this file when technology decisions are made
- **VALIDATE CHANGES**: Always test website functionality after making changes
- **BUSINESS FOCUS**: Remember this is for Nature's Way Soil business - maintain professional appearance

---

**Last Updated**: When project is initialized, update this with specific technology stack and validated commands.