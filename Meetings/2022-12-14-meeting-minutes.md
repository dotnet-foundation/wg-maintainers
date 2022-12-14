# Maintainers' Meeting 2022-12-14

## Meeting Attendees

- Rob Prouse - @rprouse
- Mattias Karlsson - @devlead
- Michael Hawker - @michael-hawker
- Nils Andresen - @nils-a
- Pascal Berger - @pascalberger
- Rob Mensching - @robmen
- Chris

## Recording

[2022-12-14 Meeting Recording](https://virtualinc-my.sharepoint.com/:v:/p/sramsey/EbB31UjhgMVIu_99EsjgEcIBO29sNAA_yD0Ea58I5Y1UKg)

### Virtual Inc Staff Observers

- Stacey Ramsey

## Agenda

- Update CLA bot
- Update Signing Service
- Other business

## Notes

- Update on the CLA bot. We are working on getting a white labelled version that requires fewer permissions.
- Signing service is using AD that is going out of support. Will be replaced by a sign CLI with new credentials. It will only work on Windows.
- When they generate passwords, could they generate a strong password without lots of symbols? My current password is terrible to try to pass in through cmd, powershell and bash. When they come through MSBuild to an `Exec` task you have to get them through CMD. Plus, you often have to test locally to make sure things are working and it's all a huge pain.
- Is that still going to be with Last Pass or will that change too?
- Projects are hard to find on the new website. The Foundation projects should be a priority.
- Wiki of questions that projects may have. CLA bot, signing service, etc.
- We need a single channel of communication channel for the Foundation
