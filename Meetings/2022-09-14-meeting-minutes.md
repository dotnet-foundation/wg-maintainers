# Maintainers' Meeting 2022-09-14

## Meeting Attendees - Slot 1

- Rob Prouse
- Mattias Karlsson
- Gary Ewan Park
- James Turner
- Robin Krom
- Shaun Walker
- Nils Andresen

## Meeting Attendees - Slot 2

- Mattias Karlsson
- Rob Prouse
- Tom Pappas
- Nicole Miller
- Stacey Ramsey
- Glenn Watson
- James Turner
- Bob Arnson
- Chika Onoh
- Daniel Valadas
- Rob Mensching

## Notes - Slot 1

### ImageSharp Licensing Changes - Slot 1

- We have Foundation licensing
- Maintainers understand wanting to see a way to monetize their projects
- One issue is that the license changes and people may not see the change when doing updates. Counter that companies should do due diligence when doing updates.
- James is doing this as a part of a major release. So that is a signal to the community.
- The CLA does not specify that the license does not change but does not specify that the work contributed will not be used for commercial purposes.
- ImageSharp does have a lot of contributions, there are 128 contributors.
- "We can still see the source code", this is a big topic I am noticing. There are people who say "Open Source" means the source is open to see, others mean open as in the "official" definition (little to no restrictions in using it) others only care about it being free. I think there is a lack of discussion GENERALLY about what open source means.
- I've seen it referred to as "source available" when it isn't strictly the OSS definition of "open source"
- Important is that it's a dual license, it's not a bait & switch in most cases.
- I guess it's a bit more complicated, reading back the license, the main license is "Six Labors Split License", which encapsulates the "Apache License version 2", and the "Six Labors Commercial License"
- James previously tried to change his license to GPLv3 but we would not allow the change
- ImageSharp's new split license is not an approved OSI license
- No matter what we do, there is going to be drama around this
- There is sympathy because it is very hard to monetize projects
- As maintainers we should understand that the .NET Foundation is not for our project if we don't want to use an OSI permissive license
- Shaun volunteered to present on Opensource sustainability at the next .NET Summit
- It would be great if the Foundation found a way to support a dual commercial license?
- If we are going to maintain some of the more complex projects long-term, the Foundation needs to find ways to help projects support themselves.
- The Foundation should first and foremost support the maintainers of projects.
- What about projects that have dependencies that may change licenses. ImageSharp allows other projects to continue to consume their opensource project but ImageSharp will still be flagged as having a non-conforming license in any Software Bill of Materials.
- Any software used to check the licenses of your software dependencies will flag ImageSharp as having a non-compliant license and none will tell you if it is a permitted transient dependency or a direct dependency. This will likely cause problems for teams at larger companies as they will need to get exceptions even for their transitive dependencies.
- Can the Foundation create an approved dual license that could be registered.
- We shared the draft announcement with the maintainers, feedback,
  - Need to state that a requirement of being in the foundation is having an approved OSI permissive license
  - The foundation allows dual-licenses but not custom licenses
  - The foundation supports projects monetizing their projects and are looking for ways to support their projects doing so
  - The statement comes across as overly formal to the point that it might come across as dismissive
  - Should start with the fact that we support projects monetizing, but we cannot support custom licenses

## Notes - Slot 2

### ImageSharp Licensing Changes - Slot 2

- Concerns about the transitive dependencies and
- How can the Foundation help projects support themselves
- Some projects can't change their licenses because they are no longer the projects' copyright holders
- Can Microsoft and the Foundation take a more friendly approach to supporting opensource projects.
- Don't support sponsorship or donation because you can't make a living on that
- How can the Foundation help change the culture around opensource and encourage companies to help fund the projects?
- Many people see the Foundation as a way for Microsoft getting free software.
- Companies don't see not supporting their opensource dependencies as a business risk as they should.
- The consulting/support model does not scale.
- Chika Onoh has been in touch with the outreach committee. Tom suggested that he join this meeting to understand the areas their committee can focus on
- Sustainable opensource
