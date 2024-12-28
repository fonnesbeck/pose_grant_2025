# Project Description

## 1. Context of OSE

Scientific computing and statistical modeling have been transformed by the advent of probabilistic programming languages and frameworks that make Bayesian inference accessible to researchers across disciplines. At the heart of this transformation are two foundational open-source projects: PyTensor, a powerful symbolic computation library, and PyMC, a probabilistic programming framework that builds upon PyTensor's capabilities. These complementary tools have enabled researchers to develop and deploy sophisticated statistical models across domains ranging from healthcare to climate science.

PyTensor emerged as a fork of Theano, inheriting and expanding upon its robust foundation for symbolic computation and automatic differentiation. As a computational backend, PyTensor provides critical capabilities including efficient automatic differentiation, GPU acceleration, and multiple compilation targets including C, JAX, and Numba. The library has grown to support over 1,000 contributors and maintains an active developer community that continually expands its capabilities. PyTensor's impact extends beyond probabilistic programming, as it serves as a foundation for research in machine learning, physics, and engineering applications.

Building upon PyTensor's computational engine, PyMC has established itself as a leading probabilistic programming framework in the Python ecosystem. PyMC empowers researchers and practitioners to construct sophisticated Bayesian models using an intuitive interface while leveraging PyTensor's performance optimizations. The framework has attracted over 1,000 contributors and garnered more than 6,700 GitHub stars, reflecting its central role in the statistical computing community. PyMC has found applications across diverse domains, from medical research and epidemiology to financial modeling and social science research.

The synergy between these two projects has created a foundation for innovation in probabilistic programming. However, the current development model, while productive, has relied heavily on informal coordination and volunteer efforts. This proposal seeks to establish a formal open-source ecosystem (OSE) that will enhance the sustainability and impact of both projects while fostering the development of complementary tools and resources.

Our vision for this ecosystem encompasses several key objectives. First, we aim to accelerate computational innovation by expanding PyTensor's capabilities, including the development of novel automatic differentiation techniques, support for emerging hardware architectures, and optimizations for specific use cases. Second, we will enable rapid advancement in statistical methodology by strengthening PyMC's core capabilities and supporting the development of specialized modeling tools. Third, we will build a more diverse and inclusive technical community by reducing barriers to entry and creating clear pathways for contributor advancement. Finally, we will nurture the development of complementary tools that extend the ecosystem's capabilities to new domains and applications.

Current analysis of the ecosystem reveals both strengths and opportunities for improvement. The active developer communities of both projects have demonstrated their ability to produce high-quality software that meets the needs of researchers and practitioners. The existing community infrastructure, including the PyMCon conference and online forums, provides a foundation for knowledge sharing and collaboration. However, several challenges must be addressed to ensure long-term sustainability. These include the need for coordinated development processes, sustainable funding for maintenance activities, formal governance structures, and improved support for new contributors.

## 2. Organization and Governance

The establishment of a robust organizational structure is essential for the long-term sustainability and growth of the PyMC/PyTensor ecosystem. We propose the creation of the PyMC Foundation, a 501(c)(3) non-profit organization that will serve as the institutional home for both projects and provide the governance framework necessary for coordinated development and community growth.

The Foundation's governance structure has been designed to balance the needs of multiple stakeholders while ensuring efficient decision-making and accountability. At its apex, a Board of Directors will provide strategic oversight and ensure alignment with the ecosystem's mission. The Board's composition reflects our commitment to diverse representation, including core developers from both PyMC and PyTensor, representatives from major institutional users, members of the broader scientific Python community, and expertise in diversity, equity, and inclusion.

Technical governance will be administered through a Technical Steering Committee (TSC) comprising experienced developers from both projects. The TSC will oversee technical decision-making, establish development priorities, and ensure coordination between PyMC and PyTensor development efforts. To maintain transparency and community input, the TSC will operate through regular public meetings and maintain detailed documentation of decisions and rationales.

Working groups will focus on specific aspects of ecosystem development, including core development, documentation, education, community engagement, and infrastructure. Each working group will be led by experienced community members and will include both established contributors and newcomers, fostering knowledge transfer and leadership development. Regular cross-working group meetings will ensure coordination and alignment of efforts.

## 3. Continuous Development Model

The success of our ecosystem depends on implementing a robust and efficient development process that supports distributed collaboration while maintaining high quality standards. Our continuous development model builds upon established best practices in open-source software development while addressing the specific needs of scientific computing projects.

The foundation of our development infrastructure will be a standardized continuous integration and deployment (CI/CD) pipeline implemented across all ecosystem projects. This pipeline will automate testing, documentation generation, and release processes, ensuring consistency and reliability. We will implement comprehensive test coverage requirements, including unit tests, integration tests, and performance benchmarks specific to numerical computing applications.

Version control and code review processes will be standardized across the ecosystem, with clear guidelines for contribution and review procedures. We will implement automated code quality checks that address both general software engineering principles and domain-specific requirements for numerical computing and statistical algorithms. Regular code sprints will be organized to tackle specific development challenges and provide opportunities for face-to-face collaboration among distributed team members.

Documentation will be treated as a first-class citizen in our development process. All new features and changes will require comprehensive documentation, including theoretical background where appropriate. We will maintain both user-facing documentation and detailed technical documentation for developers, with regular reviews to ensure accuracy and completeness.

## 4. Risk Analysis and Security Plan

The development and deployment of statistical computing software requires careful attention to security and reliability concerns. Our comprehensive risk analysis and security plan addresses potential vulnerabilities at multiple levels while ensuring the openness and accessibility that characterize successful open-source projects.

Code security will be managed through a multi-layered approach. All contributions will undergo automated security scanning using industry-standard tools adapted for scientific computing applications. We will implement mandatory code signing for releases and establish a security response team to handle vulnerability reports and coordinate responses to security incidents.

Data privacy considerations are particularly important given the sensitive nature of many statistical applications. We will establish clear guidelines for handling test data and ensure that our documentation and examples follow best practices for data privacy. The ecosystem will include tools and guidance for users implementing privacy-preserving statistical analyses.

## 5. Community Building

The long-term success of the PyMC/PyTensor ecosystem depends on cultivating a vibrant, diverse, and engaged community. Our community building strategy encompasses multiple initiatives designed to support both new and experienced contributors while expanding the ecosystem's reach and impact.

The centerpiece of our community engagement will be the transformation of PyMCon from a virtual conference into an annual in-person event supplemented by virtual components. This hybrid approach will maximize accessibility while fostering the deep connections that emerge from face-to-face interaction. The conference will feature technical presentations, tutorials, workshops, and dedicated time for collaborative development. We anticipate growing attendance from 200 participants in the first year to 500 by year three, with substantial travel support available for students and participants from underrepresented groups.

To complement the annual conference, we will establish a network of regional meetups in major scientific computing hubs. These quarterly events will provide opportunities for local community building while maintaining connections through high-quality virtual participation options. Each meetup will combine technical content with structured networking activities, fostering collaboration between academic researchers, industry practitioners, and students.

Education and training form another crucial component of our community building strategy. We will develop a comprehensive curriculum covering both the theoretical foundations and practical applications of probabilistic programming. This curriculum will be made available through multiple channels:

1. A series of online courses ranging from introductory to advanced topics
2. Workshop materials designed for university courses and industry training
3. Interactive tutorials integrated with documentation
4. Regular webinars featuring case studies and new developments

Professional development will be supported through a formal mentorship program pairing experienced developers with newcomers to the ecosystem. This program will include structured goals, regular check-ins, and clear pathways for advancement within the community. Special emphasis will be placed on recruiting and supporting contributors from underrepresented groups in scientific computing.

## 6. Sustainability Plan

Ensuring the long-term sustainability of the ecosystem requires careful attention to both financial and community resources. Our sustainability plan addresses both aspects through a diverse funding model and robust community engagement strategies.

### 6.1 Financial Sustainability

We will implement a multi-stream funding model to support ongoing development and community activities. Core funding will come from:

The Foundation will establish multiple revenue streams:

1. Corporate sponsorship program with tiered benefits including:
   - Priority technical support
   - Recognition at community events
   - Participation in technical steering committees
   - Expected annual revenue: $300,000-400,000

2. Professional services including:
   - Custom training programs
   - Technical consulting
   - Implementation support
   - Expected annual revenue: $200,000-250,000

3. Conference and event revenue:
   - Registration fees (with sliding scale)
   - Sponsorships
   - Exhibition fees
   - Expected annual revenue: $150,000-200,000

4. Research collaboration and grants:
   - Joint proposals with academic partners
   - Industry research partnerships
   - Government funding opportunities
   - Expected annual revenue: $200,000-300,000

### 6.2 Community Sustainability

Community sustainability will be achieved through structured programs for engagement and advancement:

1. Recognition and Advancement Program:
   - Clear contribution guidelines
   - Documented advancement paths
   - Regular recognition of contributors
   - Leadership development opportunities

2. Knowledge Management:
   - Comprehensive documentation
   - Best practices guides
   - Decision records
   - Training materials

3. Succession Planning:
   - Distributed responsibility model
   - Leadership rotation
   - Mentorship programs
   - Knowledge transfer protocols

## 7. Budget and Timeline ($1,150,000)

### 7.1 Personnel ($450,000)

Executive Director (0.5 FTE)
- Salary: $75,000/year
- Responsibilities: Strategic leadership, fundraising, external relations

Community Manager (1.0 FTE)
- Salary: $120,000/year
- Responsibilities: Community programs, event management, communications

Technical Project Manager (1.0 FTE)
- Salary: $140,000/year
- Responsibilities: Development coordination, technical planning, quality assurance

Benefits and overhead: $115,000

### 7.2 Events ($300,000)

Annual Conference:
- Venue and logistics: $100,000
- Travel grants: $50,000
- Program development: $25,000

Regional Meetups:
- Venue costs: $40,000
- Virtual platform: $15,000
- Materials and support: $20,000

Hackathons:
- Facilities: $30,000
- Travel support: $20,000

### 7.3 Infrastructure ($200,000)

Computing Resources:
- Cloud computing services: $60,000
- Continuous integration systems: $40,000
- Development and testing environments: $30,000

Development Tools:
- Code quality and security tools: $25,000
- Project management software: $15,000
- Documentation platforms: $15,000

Communication Infrastructure:
- Website hosting and maintenance: $8,000
- Community forum platforms: $7,000

### 7.4 Community Programs ($200,000)

Educational Materials Development:
- Course content creation: $60,000
- Tutorial development: $40,000
- Documentation writing: $30,000

Mentorship Program:
- Program coordination: $30,000
- Mentor stipends: $20,000
- Training materials: $20,000

## 8. Evaluation Plan

Our evaluation strategy employs both quantitative and qualitative metrics to assess the ecosystem's health and impact across multiple dimensions. We will implement regular assessment cycles with quarterly reviews and annual comprehensive evaluations.

### 8.1 Technical Metrics

Development Activity:
- Code contribution velocity
- Number of active contributors
- Time to close issues and pull requests
- Test coverage and documentation completeness
- Release frequency and stability

Performance Metrics:
- Computational efficiency benchmarks
- Memory usage optimization
- Compilation time improvements
- Cross-platform compatibility

### 8.2 Community Health Metrics

Participation:
- Geographic distribution of contributors
- Demographic diversity metrics
- New contributor retention rates
- Mentorship program completion rates
- Conference and event attendance

User Adoption:
- Download statistics
- Citation counts in academic literature
- Industry adoption cases
- User satisfaction surveys

### 8.3 Impact Assessment

Scientific Impact:
- Publications using PyMC/PyTensor
- Novel methodologies enabled by the ecosystem
- Integration with other scientific computing tools
- Research reproducibility metrics

Educational Impact:
- Number of courses using ecosystem tools
- Student engagement metrics
- Tutorial completion rates
- Workshop effectiveness surveys

## 9. Broader Impacts

The establishment of this open-source ecosystem will generate significant broader impacts across multiple domains:

### 9.1 Scientific Advancement

By providing robust, accessible tools for probabilistic programming, we will accelerate scientific discovery across disciplines. Researchers in fields from climate science to genomics will benefit from improved ability to quantify uncertainty and test hypotheses. The standardization of these tools will enhance reproducibility and facilitate collaboration across institutions and disciplines.

### 9.2 Education and Training

Our comprehensive educational resources will help train the next generation of data scientists and researchers in Bayesian methods and probabilistic programming. The ecosystem will provide clear pathways for students to engage with open-source development, building both technical and collaborative skills essential for modern scientific careers.

### 9.3 Diversity and Inclusion

Through targeted outreach and support programs, we will expand participation in scientific computing among underrepresented groups. Our mentorship program and travel grants will create opportunities for individuals who might otherwise face barriers to participation in the open-source community.

### 9.4 Economic Impact

The ecosystem will support innovation in industries ranging from healthcare to finance, enabling more sophisticated analysis and decision-making. By providing open-source alternatives to proprietary solutions, we will reduce barriers to entry for startups and small organizations.
