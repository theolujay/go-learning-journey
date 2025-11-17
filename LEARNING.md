# Go Learning Journal

**Purpose**: Document my 12-week journey learning Go, track insights, challenges, and growth.  
**Started**: [Your Start Date]  
**Goal**: Become a competent Go developer capable of building production-grade systems

---

## How to Use This Document

Each week, I'll add an entry covering:
1. **What I learned** - Key concepts and "aha" moments
2. **What I built** - Code and projects completed
3. **Challenges faced** - Bugs, confusion, things that didn't click
4. **Resources used** - What actually helped vs what didn't
5. **Next week's focus** - Preparation for the coming week

**Format**: Brief, honest, technical. This is for me first, portfolio second.

---

## Week 0: Setup & Orientation
**Dates**: [Start Date] - [End Date]  
**Status**: ✅ Complete

### What I Did
- Installed Go (version X.X.X)
- Configured VS Code with Go extension
- Completed Go Tour (took ~2.5 hours)
- Set up GitHub repo: `go-learning-journey`
- Created project structure with issue templates
- Set up GitHub Project board with columns
- Initialized first project: `tasks-cli`

### Key Learnings
- Go's syntax feels cleaner than Python - less "magic"
- Compilation is FAST compared to what I expected
- No implicit type conversion - have to be explicit
- Multiple return values (especially for errors) are everywhere
- The `go` tooling is impressive - `fmt`, `vet`, `test` built-in

### First Impressions (Go vs Python)
**What I Like**:
- Explicit error handling (better than try/except soup)
- Fast compilation + single binary = easy deployment
- Standard formatting (gofmt) - no more debates
- Simple syntax, less to remember

**What Feels Strange**:
- Error handling everywhere (checking `if err != nil` constantly)
- No classes - just structs and functions
- Capitalization for public/private (will take getting used to)
- Pointers are back (but simpler than C/C++)

### Challenges
- Had trouble understanding when to use pointers vs values
- `GOPATH` vs `go modules` was confusing at first (went with modules)
- Setting up issue templates took longer than expected

### Resources That Helped
- ✅ Go Tour - excellent interactive intro
- ✅ Go by Example - perfect quick reference
- ✅ VS Code Go extension - super helpful autocomplete

### Next Week
- Build basic CRUD for tasks CLI
- Deep dive into file I/O and JSON marshaling
- Start writing unit tests early
- Watch JustForFunc video on project structure

---

## Week 1: Go Fundamentals & First CLI Project
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
Master Go basics: syntax, types, control flow, functions, packages, and error handling

### Project Goal
Build CLI Todo App with basic CRUD operations and file persistence

### What I Learned
*[Fill this out as you go]*
- 
- 
- 

### What I Built
- [ ] Task struct with fields: ID, Title, Description, Done, CreatedAt
- [ ] CLI flag parsing for commands: add, list, done, delete
- [ ] JSON file storage (load/save functions)
- [ ] Basic error handling for invalid input

**Code Highlights**:
```go
// Example: The function signature that finally made sense
// [Paste a small snippet of code you're proud of or that taught you something]
```

### Challenges & Bugs
*Document problems and how you solved them*
- 

### Aha Moments
*Things that suddenly clicked*
- 

### Resources Used This Week
- [ ] Go Tour (review sections X, Y)
- [ ] Go by Example: JSON, Command-line arguments
- [ ] Video: [Title and why it helped/didn't]
- [ ] Article: [Link and key takeaway]

### Testing Notes
- Tests written: X
- Coverage: X%
- Learned: 

### Weekly Reflection
*Honest self-assessment: 2-3 sentences*
- How did this week go compared to expectations?
- What would I do differently?
- Am I on track with the roadmap?

### Next Week Preview
- Enhance task struct with more fields
- Write comprehensive tests (aim for 70%+)
- Learn about interfaces and how to use them
- Polish README and commit clean code

---

## Week 2: Data Structures & Testing
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
Structs, interfaces, slices, maps, and unit testing

### Project Goal
Enhance tasks CLI with filtering, priorities, and comprehensive tests

### What I Learned
- 
- 
- 

### What I Built
- [ ] Extended Task struct (priority, due date, tags)
- [ ] Filtering functions (by status, priority)
- [ ] Table-driven unit tests
- [ ] Test coverage report

### Code Snippets
```go
// Example: My first interface implementation
// [Paste code]
```

### Challenges & Debugging
- 

### Resources Used
- [ ] Learn Go with Tests (chapters 1-3)
- [ ] Go by Example: Structs, Interfaces, Testing
- [ ] 

### Test Results
- Coverage: X%
- Bugs found during testing: 
- What testing taught me: 

### Reflection
- 

### Next Week Preview
- Start learning concurrency (excited and nervous!)
- Begin web scraper project
- Watch videos on goroutines and channels

---

## Week 3: Concurrency Fundamentals
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
Goroutines, channels, select, sync, context

### Project Goal
Build concurrent web scraper with worker pool pattern

### What I Learned
- 
- 

### Concurrency Insights
*This is the big one - document thoroughly*
- How goroutines are different from Python's threading: 
- When to use buffered vs unbuffered channels: 
- Worker pool pattern breakdown: 

### What I Built
- [ ] Concurrent URL fetcher
- [ ] Worker pool (max N concurrent requests)
- [ ] Channel-based communication
- [ ] Context for cancellation
- [ ] Dead link detection

### Code Highlights
```go
// Worker pool implementation
// [Paste your worker pool code]
```

### Benchmarks
- Sequential scraping: X URLs in Y seconds
- Concurrent (10 workers): X URLs in Y seconds
- Speedup: Xsec → Ysec (Z% improvement)

### Challenges
*Concurrency bugs are tricky - document them*
- 

### Resources
- [ ] Concurrency in Go book (chapters 1-3)
- [ ] Dave Cheney: "Never start a goroutine..."
- [ ] 

### Reflection
- 

### Next Week
- Build HTTP API from scratch
- Learn middleware patterns
- JSON encoding/decoding deep dive

---

## Week 4: HTTP & REST APIs
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
net/http, REST principles, middleware, JSON handling

### Project Goal
Calculator API with proper routing and error handling

### What I Learned
- 
- 

### What I Built
- [ ] RESTful calculator API
- [ ] JSON request/response handling
- [ ] Input validation
- [ ] Logging middleware
- [ ] Health check endpoint

### API Design Notes
*Document your endpoint design decisions*
- 

### Code Examples
```go
// Middleware pattern
// [Paste code]
```

### Testing Strategy
- Unit tests: 
- Manual testing with curl: 

### Challenges
- 

### Resources
- [ ] roadmap.sh REST API guide
- [ ] 

### Reflection
- 

### Next Week
- Add database persistence
- Learn SQL with Go
- Integration testing

---

## Week 5: Database Integration
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
database/sql, connection pooling, SQL in Go

### Project Goal
Calculator API with history stored in SQLite

### What I Learned
- 
- 

### Database Design
```sql
-- Schema
-- [Paste your schema]
```

### What I Built
- [ ] Database layer (models)
- [ ] Calculation history storage
- [ ] GET /history endpoint with pagination
- [ ] Integration tests with test database

### SQL Gotchas
*Document tricky SQL + Go interactions*
- 

### Resources
- [ ] Practical Go Database tutorial
- [ ] 

### Reflection
- 

### Next Week
- Full-stack URL shortener
- HTML templates
- User authentication basics

---

## Week 6: Full-Stack App (Backend)
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
Templates, authentication, sessions, password hashing

### Project Goal
URL Shortener backend with user accounts

### What I Learned
- 
- 

### Authentication Approach
*Document security decisions*
- 

### What I Built
- [ ] User registration/login
- [ ] Password hashing (bcrypt)
- [ ] URL shortening logic
- [ ] Database schema (users + urls)
- [ ] User dashboard backend

### Security Considerations
- 

### Resources
- [ ] Let's Go book chapters
- [ ] 

### Reflection
- 

---

## Week 7: Full-Stack App (Frontend)
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
html/template, static files, form handling

### Project Goal
Complete URL shortener with polished UI

### What I Learned
- 

### What I Built
- [ ] HTML templates with layouts
- [ ] CSS styling
- [ ] Forms for URL creation
- [ ] Click tracking
- [ ] Copy-to-clipboard functionality

### UX Decisions
- 

### Demo
- Screenshots: [Link to images/]
- Video: [Link if recorded]

### Resources
- [ ] Template documentation
- [ ] 

### Reflection
- 

---

## Week 8: Containerization & Observability
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
Docker, multi-stage builds, logging, metrics

### Project Goal
Production-ready URL shortener with Docker and Prometheus

### What I Learned
- 

### What I Built
- [ ] Dockerfile (multi-stage)
- [ ] docker-compose.yml
- [ ] Structured logging
- [ ] Prometheus /metrics endpoint
- [ ] Deployment README

### Docker Optimization
- Initial image size: X MB
- Optimized size: Y MB
- Build time: 

### Metrics Tracked
- 

### Resources
- [ ] Prometheus Go instrumentation guide
- [ ] 

### Reflection
- 

---

## Week 9: Terminal UI Application
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
TUI frameworks, API integration

### Project Goal
Currency converter with interactive terminal interface

### What I Learned
- 

### What I Built
- [ ] Bubble Tea TUI
- [ ] Currency API integration
- [ ] Interactive currency selection
- [ ] Rate caching
- [ ] Offline mode

### TUI Framework Insights
- 

### Resources
- [ ] Charm Bracelet docs
- [ ] 

### Reflection
- 

---

## Week 10: Performance & Profiling
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
pprof, benchmarking, optimization techniques

### Project Goal
Profile and optimize existing projects

### What I Learned
- 

### Performance Improvements
**Project**: [Name]
- Before: 
- After: 
- Bottleneck found: 
- Fix applied: 

### Benchmarks
```
// Benchmark results
// [Paste results]
```

### Profiling Screenshots
- [Link to flamegraphs or pprof outputs]

### Resources
- [ ] Dave Cheney performance workshop
- [ ] 

### Reflection
- 

---

## Week 11: Capstone Project (Part 1)
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Concept Goal
[Choose: Container runtime / K8s operator / Prometheus exporter]

### Project Goal
[Your capstone project]

### What I'm Building
- 

### Architecture
[Link to architecture diagram or describe]

### Progress This Week
- [ ] 
- [ ] 
- [ ] 

### Technical Challenges
- 

### Resources
- [ ] 
- [ ] 

### Reflection
- 

---

## Week 12: Capstone Completion & Portfolio Polish
**Dates**: [Start Date] - [End Date]  
**Status**: 🔨 In Progress / ✅ Complete

### Goals
- Complete capstone
- Polish all 5 main projects
- Update GitHub profile
- Publish blog post/video

### Final Sprint Checklist
- [ ] Capstone fully functional
- [ ] All READMEs updated
- [ ] CI/CD added to main projects
- [ ] Test coverage reviewed
- [ ] Blog post published
- [ ] Video demo recorded
- [ ] LinkedIn post about completion
- [ ] Resume updated

### Capstone Final Notes
- 

### Portfolio Review
*Self-assessment of all 6 projects*
1. **Tasks CLI**: 
2. **Calculator API**: 
3. **Web Scraper**: 
4. **URL Shortener**: 
5. **Currency Converter**: 
6. **Capstone**: 

### What's Next
- 

### Final Reflection
*Looking back at 12 weeks*
- Biggest wins: 
- Hardest challenges: 
- Favorite project: 
- What surprised me about Go: 
- What I'd do differently: 
- Am I job-ready? 

---

## Resources Summary

### Most Valuable Resources
*Top 5 that actually made a difference*
1. 
2. 
3. 
4. 
5. 

### Resources That Didn't Work for Me
*So future learners can skip*
- 

### Podcast Episodes Worth Revisiting
- 

### Blog Posts That Clicked
- 

---

## Skills Gained

### Technical Skills
- [x] Go syntax and idioms
- [ ] Goroutines and channels
- [ ] HTTP servers and APIs
- [ ] Database integration
- [ ] Testing and benchmarking
- [ ] Docker and containers
- [ ] Performance profiling
- [ ] [Add more as you go]

### Soft Skills
- [ ] Breaking down large projects
- [ ] Self-directed learning
- [ ] Documentation writing
- [ ] Debugging systematically
- [ ] [Add more]

---

## Statistics

### Code Written
- Total commits: 
- Lines of Go: ~[estimate]
- Tests written: 
- Average test coverage: 

### Projects
- Completed: X/5 main + capstone
- GitHub stars received: 
- Contributions to open source: 

### Time Investment
- Total hours: ~[3-4 hrs/day × 5-6 days × 12 weeks = 216-288 hours]
- Average per week: 
- Most productive week: 

---

## What I Would Tell Someone Starting This Journey

*Fill this at the end - advice to your past self*
- 
- 
- 

---

## Acknowledgments

*People, communities, resources that helped*
- 

---

**Last Updated**: [Date]  
**Status**: Week X of 12  
**Next Review**: [Date]