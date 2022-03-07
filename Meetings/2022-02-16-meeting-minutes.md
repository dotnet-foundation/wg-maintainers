# Maintainers' Meeting 2022-02-16

## Meeting Attendees

- Rob Prouse - @rprouse
- Mattias Karlsson - @devlead
- Andrew White - @AndrewTriesToCode
- Dylan Perks - @Perksey
- Glenn Watson - @glennawatson
- James Newton-King - @JamesNK
- James Turner - @Turnerj
- Michael Hawker - @michael-hawker
- Pascal Berger - @pascalberger
- Robin Krom - @Lakritzator
- Tanner Gooding - @tannergooding

## Recording

[2022-02-16 Meeting Recording](https://dotnetfoundation-my.sharepoint.com/:v:/g/personal/rob_prouse_dotnetfoundation_org/ERjxkEaTmpZLiRL7_fwXMKwB3aioi4OX26QwOG2eaLswyg?e=QMz63d)

### Virtual Inc Staff Observers

- Nadeem Abutaa
- Tom Pappas
- Nicole Miller

## Slides

## Agenda

- Review [previous meeting minutes](2022-01-12-meeting-minutes.md)
- Leaving the .NET Foundation process
  - Walkthrough the [latest draft](https://github.com/dotnet-foundation/Home/discussions/68#discussioncomment-2168432).
  - Feedback / Q & A
  - Road map
- Signing owner lockout on nuget
- Centralizing and providing guidance to project maintainers for common questions/issues that arise and how to address them from [this thread here](https://github.com/dotnet-foundation/Home/discussions/61).
- Other business

## Notes

- Reviewed previous meeting minutes
- Introduction of new member Robin Krom
- Discussed the process to leave the foundation,
  - Tanner Gooding, it would be good to work with the NuGet team to find process for switching to unsigned packages going forward
  - How do we deal with it when the original maintainers are no longer available?
  - Discussion in the meeting that legal indicated that even if a previous maintainer passed away we'd still have to deal with the estate.
  - The original maintainers may not be available due to backpacking or other travel which is also another consideration.
  - Can we clarify that it is the non-revokable clause that is preventing us from reassigning the rights of the project and add that to the FAQ?
  - Forking the project and the foundation not continuing to maintain it is an option to leave the foundation.
  - Is four weeks notice appropriate? The four week notice could be read only and we don't need to illicit feedback.
  - One comment is that the .NET Foundation has been criticized for not communicating and a project leaving might be considered to be a big change
  - The four week notice gives the perception that the community has influence in the process
  - Would the .NET Foundation remove a maintainer if they were negatively impacting a project? By this I mean, if one was to remove major features of a project because they don't want it as part of the codebase anymore, would the Foundation step in?
  - We want to avoid doing special agreements for every project that wants to leave.
- Updating the [project benefits page PR](https://github.com/dotnet-foundation/website/pull/1085)
  - No MSDN benefit anymore
  - Looking into the Azure benefits
  - James needs more clarity, will reach out to Tom Pappas
  - We should document how members can access the benefits that are available to them.
- We'll try to get the NuGet team in a meeting about signing packages for teams that leave the foundation.
- OpenCollective, we will have discussions about what we can do, but we are looking to take on this ourselves.
- OpenCollective would allow projects to run funding for individual projects. We hope that we can provide similar functionality.

## Business that we didn't get to

Briefly discuss ()[https://github.com/dotnet-foundation/wg-maintainers/issues/48]

Talk about how we can provide better guidance to maintainers from this thread as well: [Centralised information for .NET Foundation operation](https://github.com/dotnet-foundation/Home/discussions/61)

## Action Items

- [ ] Rob and Mattias to take the comments on the process back to the board.
- [ ] Mattias to attempt to get the NuGet team in a meeting about signing packages for teams that leave the foundation and possibly finding a process for switching to unsigned packages.
- [ ] Start collecting details of projects with active managment changes and possibly get an agreement with the old maintainers to pass on legal authority for the project to the new maintainers.
