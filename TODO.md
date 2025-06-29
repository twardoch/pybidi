# PyBidi TODO List

## Immediate Tasks (High Priority)

### Packaging and Build
- [ ] Create pyproject.toml with modern build configuration
- [ ] Update setup.py to use setuptools properly
- [ ] Add proper package metadata and classifiers
- [ ] Configure version management (consider setuptools_scm)
- [ ] Add MANIFEST.in for non-Python files

### Type Safety
- [ ] Add type annotations to all functions in fribidi.py
- [ ] Create py.typed marker file
- [ ] Add mypy configuration
- [ ] Generate type stubs for better IDE support
- [ ] Run mypy in strict mode and fix all issues

### Testing
- [ ] Set up pytest framework
- [ ] Create tests/ directory structure
- [ ] Write unit tests for core functionality
- [ ] Add integration tests for library loading
- [ ] Configure GitHub Actions for CI
- [ ] Set up code coverage reporting

### Documentation
- [ ] Write comprehensive README.md to replace README
- [ ] Add installation instructions for all platforms
- [ ] Create examples/ directory with usage examples
- [ ] Add inline documentation to all public APIs
- [ ] Set up Sphinx documentation

## Short-term Tasks (Medium Priority)

### Code Quality
- [ ] Split fribidi.py into logical modules
- [ ] Set up black for code formatting
- [ ] Configure ruff or flake8 for linting
- [ ] Add pre-commit hooks
- [ ] Remove or update deprecated code patterns

### Error Handling
- [ ] Improve library loading with better error messages
- [ ] Add fallback mechanisms for missing libraries
- [ ] Create custom exception classes
- [ ] Add input validation for all public functions
- [ ] Implement proper logging instead of print statements

### Platform Support
- [ ] Test on Windows, macOS, and Linux
- [ ] Create platform-specific installation guides
- [ ] Build wheels for major platforms
- [ ] Add ARM architecture support
- [ ] Consider using cibuildwheel for releases

## Long-term Tasks (Low Priority)

### API Improvements
- [ ] Design high-level convenience API
- [ ] Add context managers where appropriate
- [ ] Implement builder pattern for complex operations
- [ ] Create async support for batch operations
- [ ] Add streaming support for large texts

### Distribution
- [ ] Publish to PyPI with wheels
- [ ] Create conda-forge recipe
- [ ] Set up automated releases
- [ ] Create Docker images for testing
- [ ] Consider bundling FriBidi library

### Community
- [ ] Add CONTRIBUTING.md guidelines
- [ ] Create issue templates
- [ ] Set up GitHub Discussions
- [ ] Add CODE_OF_CONDUCT.md
- [ ] Create security policy

### Performance
- [ ] Add performance benchmarks
- [ ] Optimize memory usage
- [ ] Consider using CFFI instead of ctypes
- [ ] Profile and optimize hot paths
- [ ] Add caching where beneficial

## Maintenance Tasks

### Regular Updates
- [ ] Update dependencies regularly
- [ ] Monitor security advisories
- [ ] Review and merge community PRs
- [ ] Maintain changelog
- [ ] Tag releases properly

### Quality Assurance
- [ ] Achieve >90% test coverage
- [ ] Fix all type checking issues
- [ ] Ensure all functions are documented
- [ ] Regular code review
- [ ] Performance regression tests