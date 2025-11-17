# Go Learning Journey

> A 12-week intensive program to master Go, build production-ready projects, and develop the skills for backend systems engineering roles.

**Status**: In Progress - Sprint 1 (Weeks 1-2)  
**Start Date**: 17th of Nov, 2025
**Portfolio**: [theolujay.dev](https://theolujay.dev)

[![Go Version](https://img.shields.io/badge/Go-1.23+-00ADD8?style=flat&logo=go)](https://go.dev/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Progress](https://img.shields.io/badge/Progress-0%25-orange)]()

---

## What's My Mission?

To level up from being a Python backend developer to a competent Go systems engineer in 12 weeks by:
- Building 6 production-grade projects
- Mastering Go's concurrency model and tooling
- Creating a portfolio that demonstrates systems thinking
- Preparing for roles at companies like Google, Uber, and cloud-native startups

---

## Now here's The Plan

### **Learning Structure**
- **Duration**: 12 weeks (3-4 hours/day, 5-6 days/week)
- **Format**: 6 two-week sprints
- **Approach**: 40% concept learning, 60% hands-on building
- **Tracking**: GitHub Projects + Notion + LEARNING.md journal

### **Core Projects I'll be working on**
#### (Dreams of Code Series + Capstone)
1. **Tasks CLI** - Command-line todo app with JSON persistence
2. **Calculator API** - RESTful service with database history
3. **Web Scraper** - Concurrent link checker demonstrating goroutines
4. **URL Shortener** - Full-stack web app with auth and analytics
5. **Currency Converter** - Terminal UI app with API integration
6. **Capstone** - Advanced systems project (container runtime / K8s operator / custom exporter)

### **Skills Development Path**
```
Weeks 1-2:  Go Fundamentals → CLI Development
Weeks 3-4:  Concurrency → HTTP Services → Databases
Weeks 5-6:  Full-Stack Development → Authentication
Weeks 7-8:  Containerization → Observability → Production Readiness
Weeks 9-10: Advanced Topics → Performance Optimization
Weeks 11-12: Systems Programming → Portfolio Polish
```

---

## What the Repo Looks Like

```
go-learning-journey/
├── projects/           # 6 main projects (each a complete Go module)
├── exercises/          # Weekly practice code and experiments
├── notes/              
│   ├── concepts/       # Deep dives on Go topics (goroutines, interfaces, etc.)
│   └── weekly/         # Technical logs for each week
├── benchmarks/         # Performance comparisons and profiling results
├── artifacts/          # Portfolio pieces (diagrams, screenshots, blog posts)
├── ROADMAP.md          # 12-week detailed learning plan
├── LEARNING.md         # Weekly learning journal
└── PROGRESS.md         # Sprint-level progress tracking
```

---

## To Journey w/Me

### Prerequisites
- Go 1.23+ installed ([installation guide](https://go.dev/doc/install))
- Git configured
- Text editor with Go support (VS Code recommended)
- Basic programming knowledge

### Clone & Setup
```bash
# Clone the repository
git clone https://github.com/theolujay/go-learning-journey.git
cd go-learning-journey

# Verify Go installation
go version

# Run tests (once projects are added)
go test ./...

# Format code
go fmt ./...
```

### Current Sprint (Weeks 1-2)
```bash
# Navigate to first project
cd projects/01-tasks-cli

# Install dependencies
go mod download

# Run the CLI
go run main.go --help

# Run tests
go test -v -cover
```

---

## Learning Resources I'll be following

### Primary Sources
- **Official**: [Go Tour](https://go.dev/tour/), [Go by Example](https://gobyexample.com/), [roadmap.sh/golang](https://roadmap.sh/golang)
- **Books**: *The Go Programming Language* (Donovan & Kernighan), *Concurrency in Go* (Cox-Buday)
- **Video**: [Anthony GG](https://www.youtube.com/@anthonygg_), [JustForFunc](https://www.youtube.com/c/justforfunc), [FreeCodeCamp Go Course](https://www.youtube.com/watch?v=un6ZyFkqFKo)
- **Podcasts**: [Go Time](https://changelog.com/gotime) (340 archived episodes)
- **Blog**: [Dave Cheney's Practical Go](https://dave.cheney.net/practical-go)

### Key Topics Covered
- ✅ Go basics: syntax, types, control flow, functions
- 🔄 Concurrency: goroutines, channels, select, context
- ⏳ Web: HTTP servers, REST APIs, middleware, templates
- ⏳ Data: SQL databases, JSON, file I/O
- ⏳ Production: Docker, logging, metrics, testing, profiling
- ⏳ Advanced: Systems programming, performance optimization

---

## I'm Actually Tracking My Progress

### Sprint Overview
| Sprint | Weeks | Theme | Status |
|--------|-------|-------|--------|
| **Sprint 1** | 1-2 | Foundations & First CLI | 🔨 In Progress |
| Sprint 2 | 3-4 | Concurrency & HTTP APIs | ⏳ Not Started |
| Sprint 3 | 5-6 | Databases & Full-Stack | ⏳ Not Started |
| Sprint 4 | 7-8 | Production & DevOps | ⏳ Not Started |
| Sprint 5 | 9-10 | Advanced & Performance | ⏳ Not Started |
| Sprint 6 | 11-12 | Capstone & Polish | ⏳ Not Started |

### Current Metrics
- **Projects Completed**: 0/6
- **Concepts Mastered**: 0/20+
- **Test Coverage**: N/A
- **Total Commits**: [Auto-update via GitHub Actions]
- **Learning Hours**: ~0/240 hours

*See [PROGRESS.md](PROGRESS.md) for detailed sprint breakdowns and [LEARNING.md](LEARNING.md) for weekly reflections.*

---

## Projects to Showcase

### 1. Tasks CLI
*Status: 🔨 In Development*

A command-line todo application demonstrating Go fundamentals.

**Features**: CRUD operations, JSON persistence, filtering, priority management  
**Concepts**: Structs, methods, file I/O, flag parsing, unit testing  
**Tech Stack**: Go stdlib, testing package

[📂 View Project](./projects/01-tasks-cli) | [📖 Docs](./projects/01-tasks-cli/README.md)

---

### 2. Calculator API
*Status: ⏳ Upcoming*

RESTful API with calculation history and database persistence.

**Features**: Math operations, request logging, history with pagination  
**Concepts**: HTTP servers, middleware, JSON, database/sql, integration testing  
**Tech Stack**: net/http, SQLite/PostgreSQL, docker

---

### 3. Web Scraper
*Status: ⏳ Upcoming*

Concurrent link checker demonstrating Go's concurrency primitives.

**Features**: Worker pools, rate limiting, dead link detection, benchmarks  
**Concepts**: Goroutines, channels, context, sync primitives  
**Tech Stack**: net/http, html parser, sync, context

---

### 4. URL Shortener
*Status: ⏳ Upcoming*

Full-stack web application with authentication and analytics.

**Features**: User auth, URL shortening, click tracking, QR codes  
**Concepts**: Templates, sessions, bcrypt, full-stack architecture  
**Tech Stack**: html/template, database, Docker, Prometheus

---

### 5. Currency Converter
*Status: ⏳ Upcoming*

Terminal UI application with external API integration.

**Features**: Interactive TUI, real-time rates, offline caching  
**Concepts**: TUI frameworks, API clients, error handling  
**Tech Stack**: Bubble Tea, HTTP clients, JSON

---

### 6. Capstone Project
*Status: ⏳ Planning*

Advanced systems-level project (final choice TBD).

**Options**: Mini container runtime, Kubernetes operator, Prometheus exporter, or custom infrastructure tool  
**Concepts**: Systems programming, advanced concurrency, cloud-native patterns  

---

## We Run Towards Tests Here

### Standards
- **Test Coverage**: Target ≥70% across all projects
- **Testing Types**: Unit tests (table-driven), integration tests, benchmarks
- **Code Quality**: All code passes `go fmt`, `go vet`, and linting
- **Documentation**: Every project has comprehensive README with examples

### Running Tests
```bash
# Run all tests
go test ./...

# With coverage
go test -cover ./...

# With race detection
go test -race ./...

# Benchmarks
go test -bench=. ./benchmarks/...

# Generate coverage report
go test -coverprofile=coverage.out ./...
go tool cover -html=coverage.out
```

---

## Insights On My Workflow

### Daily Routine
1. **Plan** (15 min): Review sprint goals, pick today's focus
2. **Build** (2-3 hours): Code, commit frequently, write tests
3. **Document** (30 min): Update notes, journal progress
4. **Reflect** (10 min): Log challenges, wins, questions

### Weekly Rhythm
- **Monday**: Sprint/weekly planning, set 3 goals
- **Tuesday-Thursday**: Build and learn (3-4 hours each)
- **Friday**: Polish code, write tests, reflect on week
- **Weekend**: Consume content (podcasts, talks) or rest

### Git Commit Convention
```
feat: Add task filtering by priority
fix: Resolve concurrent map write race condition
docs: Update README with installation steps
test: Add table-driven tests for task CRUD
refactor: Extract database logic to separate package
```

---

## Philosophy I've Chosen to Abide By

### Principles
1. **Build First, Understand Later**: Code immediately, clarify concepts as you go
2. **Test Everything**: If it's not tested, it's not done
3. **Document for Future You**: Assume you'll forget everything in 2 weeks
4. **Ship, Don't Perfect**: Done and ugly beats perfect and unfinished
5. **Learn in Public**: Share progress, ask questions, help others

### Cycle of Three (Per Week)
- **1 Concept Goal**: Master one Go concept (goroutines, interfaces, etc.)
- **1 Project Milestone**: Ship one feature or complete project phase
- **1 Artifact**: Create one visible output (README, blog post, benchmark, diagram)

---

## Ways to Catch Up w/Me

- **GitHub Project Board**: [View Sprint Progress](https://github.com/users/theolujay/projects/4/)
- **Portfolio**: [theolujay.dev](https://theolujay.dev)
- **LinkedIn**: [linkedin.com/in/theolujay](https://linkedin.com/in/theolujay)
- **Twitter/X**: [@theolujay](https://twitter.com/theolujay)

### Related Repos
- [Personal Website](https://github.com/theolujay)
- [Python Projects](https://github.com/theolujay?tab=repositories)

---

## Some Nerdy Docs

- **[ROADMAP.md](ROADMAP.md)** - Complete 12-week learning plan with weekly breakdown
- **[LEARNING.md](LEARNING.md)** - Weekly journal with reflections and insights
- **[PROGRESS.md](PROGRESS.md)** - Sprint-level tracking with metrics and retrospectives
- **[notes/concepts/](notes/concepts/)** - Deep dives on Go concepts
- **[notes/resources.md](notes/resources.md)** - Curated list of learning materials

---

## Thinking of Contributing?

This is a personal learning repository, but sure... gimme some feedback.

- **Found a bug in my code?** Open an issue
- **Have a better approach?** Open a PR with explanation
- **Want to learn together?** Reach out for accountability partnership

---

## License

MIT License - see [LICENSE](LICENSE) for details.

---

## No man should be an island

**Inspiration & Resources**:
- [roadmap.sh/golang](https://roadmap.sh/golang) - Learning path structure
- [Dreams of Code](https://www.youtube.com/@dreamsofcode) - Project ideas
- [Anthony GG](https://www.youtube.com/@anthonygg_) - Systems programming focus
- [Go Team at Google](https://go.dev) - For creating an amazing language

**Methodology Influences**:
- "Learning in Public" - Shawn Wang
- "Build to Learn" - Pragmatic Programmer philosophy
- Agile/Sprint methodology adapted for solo learning

---

## And before you go...

> "The only way to learn a new programming language is by writing programs in it." - Dennis Ritchie

This journey is about **doing**, not just consuming. Every concept learned is immediately applied to real code. Every project built teaches something new. The goal isn't perfection—it's progress, consistency, and eventually, mastery.

**Why Go?** Because it powers the infrastructure of the modern web (Docker, Kubernetes, Terraform), it's designed for systems that scale, and companies like Google value engineers who can build reliable, concurrent systems. This is about career growth, not just adding another language to the resume.

**Why Public?** Accountability, portfolio building, and helping others who might follow a similar path. If this repo helps even one person structure their Go learning, it's worth it.

---

**Last Updated**: 17th of Nov, 2025
**Current Focus**: Week 1 - Go Fundamentals  
**Next Milestone**: Complete Tasks CLI with tests (Sprint 1)

---

<p align="center">
  <sub>Built with ☕ and determination in Lagos, Nigeria (at 2 AM)</sub>
</p>