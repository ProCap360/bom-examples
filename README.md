Using a GitHub open source application example C/C++: https://github.com/google/orbit  we import the source code into ProCap 360.
We use a open source scanner - OSV to discover any CVE vulnerabilites and optionally use SonaType NexusIQ vulnerablites to score the current code.
We use a defined Infrastructure as Code (IAC) architecture with Terraform and Ansible scripts to then deploy the code on a selected infrastructure.
We then use the selected cloud service provider frameworks to score the build components.
We then apply user selected risk management frameworks to the software and release build components to give a overall security compliance score.
Three artifacts are presented in this example - a SBOM file (with found vulnerabilites) in CycloneDX 1.3 format, a Release Bill of Materials (RBOM) in CycloneDX 1.3 https://cyclonedx.org/use-cases/#service-definition and a screenshot of the ProCap360 Security Score.
