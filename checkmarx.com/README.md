# Checkmarx & Open Source


[Checkmarx](https://checkmarx.com/) is a software security company that creates solutions to help developers build security-aware applications. Checkmarx has multiple solutions that integrate into the SDLC process - static code testing (SAST and IAST), dependency analysis (SCA), supply chain security (SCS), infrastructure as code security testing (KICS), and application security training (Codebashing).

Jossef Harush Kadouri, Head of Engineering of Supply Chain Security at Checkmarx, says that the good intention of giving back to the community and enhancing the OSS realm are worth the value of publishing code as open source.

Jossef also believes that Checkmarx active participation in the OSS realm is not only good for the company brand itself, but also for their developers - The sense of community belonging and pride seeing their artifacts being employed by external users is the fuel that keeps them going and contributing to OSS projects.

Checkmarx loves contributing and creating [open source projects](https://github.com/Checkmarx). Here are some of the many projects on its [GitHub page](https://github.com/Checkmarx):

- [KICS](https://github.com/Checkmarx/kics) (i.e. Keeping Infrastructure as Code Secure) - This tool helps you find security vulnerabilities, compliance issues, and infrastructure misconfigurations early in the development cycle of your infrastructure-as-code


- [ChainAlert](https://github.com/Checkmarx/chainalert-github-action) -  A free service for the OSS community that scans popular packages (npm and more) and alerts in case there is a suspicion those packages' accounts were hacked. It compares tags on GitHub to the tags listed on the registry, and if there’s no match - It opens issues and alerts the maintainers

  <br>You can add ChainAlert's GitHub action to your repository to be notified in case of a suspected takeover of one of your dependencies, giving you the chance to rapidly respond and protect yourself and your users


- [ChainJacking](https://github.com/Checkmarx/chainjacking) - A tool that helps you find which of your Golang direct GitHub dependencies is susceptible to ChainJacking attacks. This project Can be incorporated into CI - CI process will fail if a sub-dependency is detected as exposed to ChainJacking