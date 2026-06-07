# David Gonzalez

Network Automation / GenAI Engineer focused on enterprise networking, SD-WAN,
hybrid AWS networking and practical AI-assisted infrastructure workflows.

I have 15+ years of production network infrastructure experience across Cisco
data-center, WAN, routing, VPN, segmentation, SD-WAN and change-control
environments. My current focus is building automation and GenAI-assisted tools
that help engineers parse context, validate changes, generate MOPs, explain
network behavior and preserve operational knowledge.

## Featured Projects

| Project | What it demonstrates |
| --- | --- |
| [network-genai-knowledge-assistant](https://github.com/folk00/network-genai-knowledge-assistant) | Python/PySide6 GenAI knowledge assistant with Claude/OpenAI-style workflows, RAG-style retrieval, citations, diagrams, report persistence and safety boundaries. |
| [hybrid-tgw-vpn-terraform](https://github.com/folk00/hybrid-tgw-vpn-terraform) | AWS Transit Gateway + Site-to-Site VPN lab using Terraform, with Linux strongSwan and Cisco C8000v customer gateway paths. |
| [network-automation-framework](https://github.com/folk00/network-automation-framework) | Multi-vendor network automation framework using Python/Ansible-style structure with Cisco IOS and Arista cEOS/containerlab testing concepts. |
| [ops-portal](https://github.com/folk00/ops-portal) | Operational infrastructure portal patterns for network/cloud workflow automation. |
| [cloud-microstack](https://github.com/folk00/cloud-microstack) | Cloud-native microstack with Next.js/FastAPI and AWS/Terraform infrastructure references. |

## Current Focus

- Network automation with Python, Netmiko and Ansible-style workflows
- Applied GenAI for network troubleshooting, review and documentation
- RAG-style retrieval, citations and controlled LLM workflows
- AWS networking: VPC, Transit Gateway, Site-to-Site VPN, Direct Connect concepts
- Cisco SD-WAN, Nexus/Catalyst, routing, VPN and enterprise migration workflows

## Certifications

- AWS Certified Advanced Networking - Specialty
- AWS Certified Solutions Architect - Associate
- Cisco CCNP Enterprise
- Cisco DevNet Associate
- Cisco SD-WAN Implementation Specialist

## How I Think About GenAI

The useful pattern is not "chat with a model." It is deterministic software plus
bounded model reasoning:

```text
network input / MOP / config / incident
  -> parse and structure context
  -> retrieve relevant evidence
  -> call an LLM inside a controlled workflow
  -> produce cited explanations, validation steps or reports
  -> keep a human in the loop
```

That is the pattern these projects are building toward.
