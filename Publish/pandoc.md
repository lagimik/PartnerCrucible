# Publishing with pandoc

## Purpose

Sometimes you need to compile things into a document. Pandoc can be used for combining and converting Markdown pages into an Microsoft Word document.

the following command will produce a MS word document with a table of contents using a list of markdown documents as input:

A sample output is here: [Partner Crucible](./PartnerCrucible.docx)

## Command
```
pandoc --toc -s -o ./Publish/PartnerCrucible.docx README.md ContributorsGuide.md PartnerPortals.md PartnerSupport.md SolutionPartners.md ./Taxonomy SolutionPartners.md LearningResources.md PracticeBuilding.md SalesEnablement.md CSP.md SaaS.md CommercialMarketplaceOffers.md ModernWorkSolutionArea.md PowerPlatformSolutionArea.md BusinessApplicationsSolutionArea.md SecuritySolutionArea.md SecuritySolutionArea-Sentinel.md  AzureDefenderIoT.md DigitalAppsandInnovationSolutionArea.md AIIOTInsiderLab.md MixedReality.md AzureInfrastructureSolutionArea.md  AzureInfrastructureSolutionArea-LandingZones.md Hackathon.md SandboxEnvironments.md  IndustryCanadianPublicSector.md MicrosoftAccessibility.md IndustryFinancialServices.md IndustrySustainability.md IndustryTelecom.md IndustryGeneral.md InnovationatMicrosoft.md 
```
```
ggit log  --abbrev-commit --name-status --decorate --format=format:'%as | %s | [See changes here](./)' --all 
```
## References


Source | Description | Notes
:----- | :-----  | :-----
[Pandoc](https://pandoc.org/) | If you need to convert files from one markup format into another, pandoc is your swiss-army knife..

