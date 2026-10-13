# Data Engineering Tools & Notebooks

**A collection of practical tools, reusable notebooks, and automation utilities for modern data engineering.**

This repository contains tools, scripts, notebooks, and implementation examples designed to solve real-world challenges in data engineering, analytics, cloud platforms, and data operations.

The primary focus is Microsoft Fabric and the Microsoft data ecosystem, with additional resources for Azure, Python, Apache Spark, SQL, and related technologies.

Rather than providing isolated code snippets, the goal is to share **practical, reusable solutions** that can be adapted to different environments and projects.

## Objectives

- **Solve real problems:** Share utilities developed around practical engineering and operational challenges.
- **Promote reusability:** Build configurable tools that can be applied across multiple projects and environments.
- **Simplify administration:** Automate repetitive tasks and reduce manual operational effort.
- **Share knowledge:** Document implementation approaches, technical considerations, and lessons learned.
- **Encourage collaboration:** Provide examples that others can extend, improve, and contribute to.

## 🛠️ Technologies

The repository may include resources related to:

- **Microsoft Fabric:** Lakehouse, Warehouse, Notebooks, Data Pipelines, Dataflows Gen2, OneLake, and REST APIs.
- **Apache Spark & PySpark:** Distributed processing, Delta Lake, performance optimization, and data transformations.
- **Microsoft Azure:** Cloud integrations, storage, automation, and data services.
- **Python:** Administrative utilities, data processing, API integrations, and automation.
- **SQL:** Data engineering patterns, query optimization, and database operations.
- **Power BI:** Semantic models, performance considerations, and analytical solutions.


The directory structure will evolve as new utilities and examples are added.

## Available Tools

### Microsoft Fabric

| Tool | Description | Technology |
|---|---|---|
| Fabric Workspace Recycle Bin Cleaner | Inspect and permanently delete eligible items from a Microsoft Fabric Workspace recycle bin using REST APIs, with safeguards and dry-run support. | Python, Fabric REST API |

Additional tools and notebooks will be published progressively.

## Getting Started

1. Browse the repository and select the tool or notebook that addresses your scenario.
2. Read its documentation, prerequisites, and required permissions.
3. Download or clone the repository.
4. Configure the parameters for your environment.
5. Test the solution in a non-production environment before using it in production.

Each utility should include its own usage instructions, configuration details, and relevant technical considerations.

## Security and Best Practices

The utilities in this repository are intended to encourage safe, maintainable, and responsible automation.

Before executing any tool:

- Review the source code and understand its behavior.
- Use the principle of least privilege.
- Never hardcode credentials, tokens, or confidential information.
- Validate permissions and configurations.
- Prefer dry-run or preview modes when supported.
- Exercise additional caution with destructive operations.
- Test changes before implementing them in production.

**Important:** Some utilities perform administrative actions, including permanent deletion of resources. Always review their impact and ensure that you have the appropriate authorization.

## Contributions

Contributions, suggestions, issue reports, and improvements are welcome.

If you have an idea for a new utility, discover an issue, or want to improve an existing implementation, feel free to open an issue or submit a pull request.

The objective is to build a practical collection of resources that benefits the broader data engineering community.

## Documentation and References

Where applicable, utilities will reference official documentation from Microsoft and other technology providers.

Key resources:

- [Microsoft Fabric Documentation](https://learn.microsoft.com/en-us/fabric/)
- [Microsoft Fabric REST API](https://learn.microsoft.com/en-us/rest/api/fabric/)
- [Microsoft Fabric Notebooks](https://learn.microsoft.com/en-us/fabric/data-engineering/how-to-use-notebook)
- [Apache Spark Documentation](https://spark.apache.org/docs/latest/)
- [Delta Lake Documentation](https://docs.delta.io/)

## Disclaimer

The code and examples in this repository are provided for educational, demonstration, and reference purposes.

Although the tools are designed with reusability and operational considerations in mind, they may require adjustments for specific environments, configurations, permissions, and platform versions.

Always review, validate, and test the code before deploying it in production.

The repository is an independent community resource and is not an official Microsoft product.

---

**Built from real-world data engineering challenges. Shared to make everyday engineering easier.**

⭐ If you find these tools useful, consider starring the repository.
