# Partnership Structure
## Shopify Hydrogen Migration Partnership

### Overview

This document outlines the proposed structure for the Shopify Hydrogen Migration Partnership, detailing entity relationships, roles and responsibilities, governance framework, and intellectual property arrangements.

### Entity Relationship Diagram

```
┌───────────────────────┐
│                       │
│  JJJNJWMBB Holdings   │◄────────┐
│  (Master Entity)      │         │
│                       │         │
└───────────┬───────────┘         │
            │                     │
            │                     │
            │                     │
┌───────────▼───────────┐         │
│                       │         │
│    Client Contract    │         │
│                       │         │
└───────────┬───────────┘         │
            │                     │
            ├───────────────┬─────┼─────────────┐
            │               │     │             │
┌───────────▼─────┐ ┌───────▼─────▼───┐ ┌───────▼────────┐ ┌───────────────┐
│               │ │                 │ │                │ │               │
│  Cactus Labs  │ │  Atomic Social  │ │ JN Development │ │ Lead Partners │
│  (Tech IP)    │ │  (Service)      │ │ (Development)  │ │ (Sourcing)    │
│               │ │                 │ │                │ │               │
└───────────────┘ └─────────────────┘ └────────────────┘ └───────────────┘
```

### Entity Descriptions and Roles

#### 1. JJJNJWMBB Holdings
**Role**: Master contracting entity, governance, and financial management

**Key Responsibilities**:
- Contracting with end clients
- Financial administration and distribution
- Partnership governance and conflict resolution
- Strategic direction and oversight

**Board Composition**:
- Wyatt & Matt (Cactus Labs)
- Noah & Jordan (JJ&N Holdings) 
- Brian & Ben (Atomic Social)
- Bert (H&M Media)

**Notes**: This entity structure has been streamlined from the original concept to provide clearer lines of authority and simpler contracting relationships. A single master entity reduces client confusion and simplifies financial administration.[^1]

#### 2. Cactus Labs
**Role**: Technology IP owner and technical leadership

**Key Responsibilities**:
- Development and maintenance of Hydrogen frameworks and templates
- Technical architecture design and oversight
- Technology standards and quality assurance
- Technical leadership on client implementations
- Developer training and enablement

**Key Personnel**:
- Technical/Integration Lead (per implementation)
- Hydrogen Lead (Ash)
- Design Lead (Jacob)

**Licensing Arrangements**:
- Licenses Hydrogen project templates to Holdings
- Licenses migration frameworks and processes to Holdings
- Licenses maintenance and support framework to Holdings

#### 3. Atomic Social
**Role**: Client-facing service delivery and marketing strategy

**Key Responsibilities**:
- Client relationship management
- Project management
- Marketing and optimization strategy
- Service delivery coordination
- Client onboarding and training

**Key Personnel**:
- Project Manager
- E-commerce Development (augmenting Cactus Labs)
- Design Lead (augmenting Cactus Labs)

**Product/Service Offering**:
- Shopify Migrations (Liquid to Hydrogen)
- Price range: $25K-$100K based on scope and complexity

#### 4. JN Development Group
**Role**: Core development resources and technical implementation

**Key Responsibilities**:
- Development resource provision
- Technical implementation
- Quality assurance and testing
- Technical documentation

**Key Personnel**:
- Up to 3 developers per project
- Technical Lead (fallback order: 1st - IP; 2nd - OP; 3rd - MP, 4th - SP)
- 2 Senior Developers as needed

#### 5. JN Management Group
**Role**: Technical management and orchestration

**Key Responsibilities**:
- Technical project management
- Resource allocation and scheduling
- Technical standards enforcement
- Process and methodology oversight

**Licensing Arrangements**:
- Holdings licenses hydrogen SDLC (bundling Cactus licenses, component design system, processes) to Atomic Social

#### 6. Marketing Partners
**Entities**: H&M Media, Digital Interactive

**Role**: Lead generation and qualification

**Key Responsibilities**:
- Identifying potential clients
- Initial qualification
- Brand positioning support
- Marketing strategy input

**Commercial Terms**:
- Source Percentage: ~10% each

### Revised Governance Framework

#### Board of Directors (JJJNJWMBB Holdings)
- Quarterly strategic meetings
- Approval of annual business plans
- Major partnership decisions
- Conflict resolution (final authority)

#### Executive Committee
- Monthly operational meetings
- Composed of one representative from each key partner
- Operational decisions and resource allocation
- KPI tracking and performance monitoring

#### Project Steering Committee
- Formed for each major client engagement
- Includes technical and delivery leads
- Weekly progress monitoring
- Issue resolution and scope management

### Decision-Making Matrix

| Decision Type | Authority | Consultation Required | Notification |
|---------------|-----------|----------------------|--------------|
| Client Contract Approval | Holdings Board | All Partners | Marketing Partners |
| Technical Architecture | Cactus Labs | JN Development | Atomic Social |
| Project Staffing | JN Management | Affected Partners | Holdings Board |
| Service Pricing | Holdings Board | Atomic Social | All Partners |
| Marketing Materials | Atomic Social | H&M Media | All Partners |
| Resource Allocation | JN Management | Affected Partners | Holdings Board |
| IP Development | Cactus Labs | JN Development | Holdings Board |
| Partnership Changes | Holdings Board | All Partners | N/A |

### IP and Licensing Structure

#### Owned IP

| IP Asset | Owner | Licensed To | Terms |
|----------|-------|------------|-------|
| Hydrogen Project Templates | Cactus Labs | Holdings | Per-use fee with annual minimums |
| Component Design System | Cactus Labs | Holdings | Annual license fee |
| Integration Frameworks | Cactus Labs | Holdings | Per-project license |
| Maintenance Framework | Cactus Labs | Holdings | Revenue share on maintenance contracts |
| SDLC Process Bundle | Holdings | Atomic Social | Per-project license fee |
| Marketing Materials | Atomic Social | All Partners | Royalty-free internal use |
| Case Studies | Holdings | All Partners | Attribution required |

#### IP Development Process

1. **Identification**: Partners identify potential IP development opportunities
2. **Approval**: Holdings Board approves IP investment
3. **Development**: Appropriate partner develops the IP
4. **Documentation**: Comprehensive documentation created
5. **Licensing**: Formal licensing structure established

### Operational Workflow

```
┌──────────────┐     ┌──────────────┐     ┌────────────────┐
│ Lead Partner │────►│ Atomic Social│────►│ JJJNJWMBB      │
│ (Sourcing)   │     │ (Qualifying) │     │ (Contracting)  │
└──────────────┘     └──────────────┘     └────────┬───────┘
                                                   │
                                                   ▼
┌──────────────┐     ┌──────────────┐     ┌────────────────┐
│ Cactus Labs  │◄────┤ JN Management│◄────┤ JN Development │
│ (Technical)  │     │ (Orchestrate)│     │ (Development)  │
└──────┬───────┘     └──────┬───────┘     └────────────────┘
       │                    │                      ▲
       └────────────────────┼──────────────────────┘
                            │
                            ▼
                     ┌──────────────┐
                     │ Atomic Social│
                     │ (Delivery)   │
                     └──────┬───────┘
                            │
                            ▼
                     ┌──────────────┐
                     │    Client    │
                     └──────────────┘
```

### Partner Integration Points

#### Technical Integration
- Cactus Labs provides technical framework and standards
- JN Development implements according to frameworks
- JN Management ensures technical quality and standards compliance
- Atomic Social integrates marketing optimization requirements

#### Operational Integration
- Shared project management tools across partners
- Standardized reporting templates
- Common communication channels
- Regular coordination meetings

#### Financial Integration
- Centralized billing through Holdings
- Standardized invoicing between partners
- Transparent financial reporting
- Regular reconciliation process

### Changes from Original Structure

Several refinements have been made to the original partnership concept:[^2]

1. **Simplified Client Contracting**: All client contracts now flow through the Holdings entity rather than multiple contracting relationships, reducing complexity and potential conflicts.

2. **Clearer Authority Lines**: Defined decision-making matrix with clear authority, consultation, and notification requirements.

3. **Enhanced Governance**: Added project steering committees for implementation oversight and an executive committee for operational coordination.

4. **Formalized IP Structure**: Added comprehensive IP ownership and licensing framework to protect partner contributions and ensure proper value attribution.

5. **Streamlined Workflow**: Defined clear operational workflow to ensure smooth handoffs between partners and consistent client experience.

### Next Steps

1. **Partnership Agreement Development**
- [ ] Draft master partnership agreement
- [ ] Develop IP licensing agreements
- [ ] Create service level agreements between partners
- [ ] Establish revenue sharing framework

2. **Governance Implementation**
- [ ] Schedule initial Holdings Board meeting
- [ ] Appoint Executive Committee members
- [ ] Establish meeting cadence and reporting structure
- [ ] Develop decision documentation process

3. **Operational Alignment**
- [ ] Select shared project management tools
- [ ] Develop partner onboarding documentation
- [ ] Create common templates and processes
- [ ] Define escalation procedures

4. **Team Formation**
- [ ] Identify key personnel from each partner
- [ ] Conduct cross-partner orientation
- [ ] Establish communication channels
- [ ] Schedule initial team building activities

[^1]: The simplified entity structure reduces legal complexity and potential tax issues while maintaining the collaborative spirit of the partnership. This approach is common in joint ventures where multiple specialized entities contribute to service delivery.

[^2]: These refinements address potential points of friction in the original concept while maintaining the core value proposition and partner relationships. The clearer structure will support scale and reduce operational overhead.

---

**TODO Items:**
- [ ] Create detailed RACI matrix for all key activities
- [ ] Develop standardized inter-partner SLAs
- [ ] Draft Holdings operating agreement
- [ ] Create partner onboarding documentation
- [ ] Define conflict resolution procedures
- [ ] Establish IP valuation methodology 