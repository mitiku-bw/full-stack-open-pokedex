# CI/CD: Exercise 11.1
1. Some common steps in a CI setup include _linting, testing, and building_. There many tools for taking care of these steps in JS code. Some of the most common ones are:
    * Linting - JSHint, JSLint, ESLint and Standard JS
    * Testing - Mocha, Jest, Jasmine, Karma, Puppeteer, Nightwatch, Cypress and Protractor.
    * Building - Vite, ESBuild, Rome toolchain, Webpack, TSdx, Parcel, Rollup, Microbundle, Wmr, Lasso.js, snowpack, etc.
1. The following are some of the alternatives to set up the CI besides Jenkins and GitHub Actions:
    * GitLab
    * Atlassian Bamboo
    * JFrog Pipelines
    * Spinnaker
    * JetBrains TeamCity
    * AWS CodePipeline
    * Azure DevOps Server (formerly Microsoft Team Foundation Server)
    * Maven and Gradle
    * CloudBees CI (formerly CloudBees Core)

    Source:  [10 Jenkins alternatives for developers](https://www.theserverside.com/tip/5-Jenkins-alternatives-for-Java-developers)
1. Deciding whether to use self-hosted or a cloud-based environment CI/CD system depends on the needs of the team/user
    * ## Self-Hosted CI/CD Services
        If you are self-hosting your CI/CD systems, you will be responsible for making infrastructure decisions, keeping the underlying servers healthy by servicing hardware and patching software, and ensuring the services are available, secure, and performing adequately. This is a large scope of additional responsibility that may fall outside of your team’s expertise and beyond what you’re able to budget time for. 
        Because the CI/CD system has broad security access and is essential to developing trust in the changes you push to your projects, it is essential that your team treats it as a critical — rather than supplementary — component. Downtime of your continuous systems can affect the productivity and capabilities of your entire team. While the CI/CD system is not your main project and is meant to be a tool to help your organization, responsibility for managing it should not be taken lightly.
        Another major difference between using a managed provider and self-hosting your own continuous integration, delivery, and deployment service is the interplay between security and trust. Your CI/CD system will have access to your codebase and the ability to deploy to multiple environments. This means that you need to focus heavily on the security of your CI/CD systems. For managed solutions, you additionally need to evaluate your trust in the external provider.
    * ## Cloud CI/CD Services
        Cloud/managed services are completely hosted and supervised by an external organization offering CI/CD capabilities. The external organization takes responsibility for running and scaling their services, maintaining the health of their server fleet, and providing access to the services in a secure and easy to consume way. This is usually the largest value that managed CI/CD services provide and, in effect, can offload a large amount of work from your team by encapsulating and abstracting complexity.
        While cloud solutions delegate a portion of the work and allow your teams to focus on other concerns, there are areas where externalizing control over your infrastructure may not be a good idea. If compliance or your own organizational standards demand tight control over your processes, strictly regulated access to your code or data, or include special requirements that external partners are unable to guarantee, managing your own services might be your only option.
    * ## Conclusion
        Both cloud CI/CD providers and self-hosted solutions can help improve your development and release practices to deliver more reliable products with more confidence. We’ve covered the most important differences between these two main options, some of the factors that may affect your decision, and the potential challenges you will have to overcome with each choice. We also talked briefly about offerings that attempt to straddle the line between self-hosting and managed solutions. In the end, your organization’s unique requirements, budget, and administration bandwidth will help you decide which option offers the right tradeoffs.
    
        Source: [CI/CD Comparison: Using Managed Providers vs Self-Hosting](https://www.digitalocean.com/community/tutorials/ci-cd-comparison-using-managed-providers-vs-self-hosting#managing-infrastructure)
