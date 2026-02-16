# 📐 System Design Mastery Plan
*A 3-Week Journey for Caroline - From Amazon L5 to NYC Tech Senior*

## 🎯 Overview
**Target**: Senior SDE roles at NYC tech companies (Stripe, Datadog, MongoDB, Two Sigma, etc.)
**Time Investment**: 5-7 hours/week (alongside your LC practice)
**Current Level**: L5 SDE at Amazon (backend infra, virtual tables, internal tools)
**Goal**: Master system design interviews for senior positions

---

# Week 1: Foundations & Core Concepts
*"Building the Foundation"*

## Day 1-2: System Design Fundamentals (2-3 hours)
### Theory & Concepts
- [ ] **Scalability principles**: Horizontal vs Vertical scaling
- [ ] **Load Balancing**: Round robin, weighted, consistent hashing
- [ ] **Caching strategies**: Cache-aside, write-through, write-behind
- [ ] **Database concepts**: ACID, CAP theorem, eventual consistency
- [ ] **Microservices vs Monoliths**: When to use each

### Resources
- [ ] 📖 **Read**: Designing Data-Intensive Applications (Ch 1-2) - Martin Kleppmann
- [ ] 🎥 **Watch**: "Scalability for Dummies" series by Gaurav Sen (YouTube)
- [ ] 📝 **Practice**: Draw a simple 3-tier architecture

## Day 3-4: Storage & Databases (2-3 hours)
### Deep Dive Topics
- [ ] **SQL vs NoSQL**: When to use MySQL vs MongoDB vs Cassandra
- [ ] **Database sharding**: Consistent hashing, shard keys
- [ ] **Replication**: Master-slave, master-master
- [ ] **Data modeling**: Normalization vs denormalization

### Hands-on Practice
- [ ] **Problem**: Design a simple key-value store
- [ ] **Problem**: Design a basic chat message storage system

### Resources
- [ ] 📖 **Read**: High Performance MySQL (Ch 1-3)
- [ ] 🎥 **Watch**: "Database Sharding" by Hussein Nasser
- [ ] 🔗 **Study**: AWS DynamoDB design patterns (relevant to your AWS exp)

## Day 5-7: Networking & Communication (2 hours)
### Key Concepts
- [ ] **API Design**: REST vs GraphQL vs gRPC
- [ ] **Message Queues**: Kafka, RabbitMQ, SQS
- [ ] **Content Delivery**: CDNs, edge caching
- [ ] **Service mesh**: Basic concepts (Istio, Envoy)

### Mini Projects
- [ ] **Exercise**: Design API endpoints for a social media app
- [ ] **Exercise**: Choose message queue vs direct API calls for different scenarios

### Resources
- [ ] 📖 **Read**: Building Microservices (Ch 4-5) - Sam Newman
- [ ] 🎥 **Watch**: "Message Queues Explained" by Tech Dummies
- [ ] 📝 **Document**: Create your own "When to use what" cheat sheet

---

# Week 2: Classic System Design Problems
*"The Interview Essentials"*

## Day 1-2: Social Media & Content (3 hours)
### Problems to Master
- [ ] **Design Twitter** (start here - foundational problem)
  - Timeline generation (push vs pull model)
  - Tweet storage and retrieval
  - Follower/following relationships
  - Real-time updates
- [ ] **Design Instagram**
  - Photo upload and storage
  - Feed generation
  - Image processing pipeline

### Practice Approach
1. **45 min per problem**: Follow the standard interview format
2. **Requirements gathering** (5 min)
3. **Estimation** (5 min)  
4. **High-level design** (15 min)
5. **Detailed design** (15 min)
6. **Scale & optimize** (5 min)

### Resources
- [ ] 📖 **Study**: "System Design Interview" by Alex Xu (Ch 11-12)
- [ ] 🎥 **Watch**: "Design Twitter" by Exponent
- [ ] 📝 **Practice**: Draw both solutions on whiteboard/iPad

## Day 3-4: E-commerce & Payments (2-3 hours)
### Problems to Master
- [ ] **Design Amazon/E-commerce platform**
  - Product catalog
  - Inventory management
  - Order processing
  - Search functionality
- [ ] **Design Payment System**
  - Payment processing flow
  - Fraud detection
  - Transaction consistency
  - PCI compliance considerations

### Amazon-Specific Insights
- [ ] Leverage your internal knowledge of Amazon's architecture
- [ ] Think about how virtual tables might scale
- [ ] Consider Amazon's approach to eventual consistency

### Resources
- [ ] 📖 **Read**: "Designing Distributed Systems" (Ch 8-9) - Brendan Burns
- [ ] 🎥 **Watch**: "Payment System Design" by Gaurav Sen
- [ ] 🔗 **Explore**: Stripe's API documentation (excellent design patterns)

## Day 5-7: Infrastructure & Tools (2 hours)
### Problems to Master
- [ ] **Design URL Shortener** (bit.ly, tinyurl)
  - Custom short URLs
  - Analytics tracking
  - Rate limiting
  - Cache optimization
- [ ] **Design Web Crawler**
  - Distributed crawling
  - Duplicate detection
  - Rate limiting per domain
  - Content parsing

### Resources
- [ ] 📖 **Study**: "System Design Interview" by Alex Xu (Ch 8-9)
- [ ] 🎥 **Watch**: "Design URL Shortener" by Tech Dummies
- [ ] 💡 **Bonus**: Think about how these relate to your internal tools work

---

# Week 3: Advanced Topics & Mock Practice
*"Senior-Level Mastery"*

## Day 1-2: Advanced Distributed Systems (3 hours)
### Complex Problems
- [ ] **Design Uber/Lyft**
  - Real-time location tracking
  - Matching algorithms
  - ETA calculations
  - Dynamic pricing
- [ ] **Design Netflix**
  - Video streaming
  - Content recommendation
  - Global CDN strategy
  - A/B testing platform

### Advanced Concepts
- [ ] **Consensus algorithms**: Raft, Paxos (high-level understanding)
- [ ] **Event sourcing**: When and how to use
- [ ] **CQRS**: Command Query Responsibility Segregation
- [ ] **Distributed transactions**: 2PC, Saga pattern

### Resources
- [ ] 📖 **Read**: "Designing Data-Intensive Applications" (Ch 7-9)
- [ ] 🎥 **Watch**: "Design Netflix" by Success in Tech
- [ ] 📝 **Practice**: Solve one problem focusing purely on scale (1B+ users)

## Day 3-4: Observability & Reliability (2 hours)
### System Design for Production
- [ ] **Design Monitoring System** (Datadog-style)
  - Metrics collection
  - Log aggregation
  - Alerting system
  - Dashboard generation
- [ ] **Chat System Design** (Slack/Discord)
  - Real-time messaging
  - Channel management
  - Message history
  - Online presence

### Production Readiness
- [ ] **SLA/SLO concepts**: Availability, latency percentiles
- [ ] **Circuit breaker pattern**
- [ ] **Bulkhead pattern**
- [ ] **Graceful degradation**

### Resources
- [ ] 📖 **Read**: "Site Reliability Engineering" (Ch 4-6) - Google SRE Book
- [ ] 🎥 **Watch**: "Building Resilient Systems" by AWS re:Invent
- [ ] 🔗 **Study**: Datadog's architecture blog posts

## Day 5-7: Mock Interviews & Polish (2-3 hours)
### Mock Practice Schedule
- [ ] **Day 5**: Mock #1 - Pick a random problem, time yourself (45 min)
- [ ] **Day 6**: Mock #2 - Focus on a problem you struggled with
- [ ] **Day 7**: Mock #3 - New problem, simulate real interview pressure

### Interview Polish
- [ ] **Communication practice**: Explain your thinking out loud
- [ ] **Whiteboard skills**: Clean diagrams, readable text
- [ ] **Question handling**: Ask clarifying questions naturally
- [ ] **Trade-off discussions**: Always discuss pros/cons

### Final Prep Materials
- [ ] 📋 **Create**: Your personal system design template
- [ ] 📋 **Review**: Common numbers to remember (latencies, throughput)
- [ ] 📋 **Prepare**: Your "go-to" technologies and why you choose them

### Resources
- [ ] 🎥 **Watch**: Real system design interviews on YouTube
- [ ] 📝 **Practice**: pramp.com or interviewing.io for mock sessions
- [ ] 🎯 **Book**: Schedule real mock interviews with friends/colleagues

---

# 📚 Essential Resources

## 📖 Books (Priority Order)
1. **"System Design Interview"** by Alex Xu - Best interview prep
2. **"Designing Data-Intensive Applications"** by Martin Kleppmann - Deep theory
3. **"Building Microservices"** by Sam Newman - Architecture patterns
4. **"High Performance MySQL"** - Database optimization
5. **"Site Reliability Engineering"** by Google - Production systems

## 🎥 YouTube Channels
- **Gaurav Sen** - Excellent system design tutorials
- **Tech Dummies** - Clear explanations with diagrams
- **Hussein Nasser** - Deep database and networking content
- **Success in Tech** - Mock interview practice
- **Exponent** - FAANG-focused interview prep

## 🔗 Online Resources
- **High Scalability** (highscalability.com) - Real system architectures
- **AWS Architecture Center** - Cloud design patterns
- **Engineering blogs**: Uber, Netflix, Twitter, Pinterest, LinkedIn
- **System Design Primer** (GitHub) - Comprehensive reference

## 🛠️ Tools for Practice
- **Draw.io** or **Lucidchart** - System diagrams
- **Excalidraw** - Quick sketches and mockups
- **Pramp.com** - Free mock interviews
- **LeetCode System Design** - Premium practice problems

---

# 🎯 NYC Tech Company Focus

## Target Companies & Their Known Preferences
- **Stripe**: Payment systems, API design, reliability
- **Datadog**: Monitoring, observability, time-series data
- **MongoDB**: Database design, sharding, replication
- **Two Sigma**: High-frequency systems, latency optimization
- **Palantir**: Data processing, graph databases
- **Oscar Health**: Healthcare systems, compliance, data privacy
- **Compass**: Real estate platforms, search, recommendations

## Common NYC Interview Patterns
- **Emphasis on production systems**: How do you monitor/debug/scale?
- **Business context**: Understanding the business problem before jumping to tech
- **Team collaboration**: How would you work with product/design teams?
- **Cost considerations**: AWS costs, infrastructure efficiency

---

# ✅ Success Metrics

## Week-by-Week Goals
**Week 1**: Confidently explain fundamental concepts, draw basic architectures
**Week 2**: Solve classic problems in 45 minutes with good structure
**Week 3**: Handle advanced scenarios, discuss trade-offs like a senior engineer

## Interview Readiness Checklist
- [ ] Can draw clean system diagrams in 15 minutes
- [ ] Naturally ask clarifying questions
- [ ] Discuss 3-4 different approaches for each problem
- [ ] Explain trade-offs without prompting
- [ ] Handle follow-up questions confidently
- [ ] Connect solutions to real-world experience

## Caroline's Advantages
✅ **Amazon experience**: You understand scale, distributed systems, operational excellence
✅ **Backend infrastructure**: Virtual tables, internal tools - perfect system design background  
✅ **LC practice**: You already have the problem-solving mindset
✅ **2.5 years experience**: You've seen real production systems

---

*Built with 🐙 by Aria for Caroline's NYC tech journey*
*Remember: You're not just learning system design - you're showing your expertise!*