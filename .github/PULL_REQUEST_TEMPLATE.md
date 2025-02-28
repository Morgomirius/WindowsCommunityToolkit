<!-- 🚨 Please Do Not skip any instructions and information mentioned below as they are all required and essential to evaluate and test the PR. By fulfilling all the required information you will be able to reduce the volume of questions and most likely help merge the PR faster 🚨 -->

<!-- 👉 It is imperative to resolve ONE ISSUE PER PR and avoid making multiple changes unless the changes interrelate with each other -->

<!-- 📝 Please always keep the "☑️ Allow edits by maintainers" button checked in the Pull Request Template as it increases collaboration with the Toolkit maintainers by permitting commits to your PR branch (only) created from your fork. This can let us quickly make fixes for minor typos or forgotten StyleCop issues during review without needing to wait on you doing extra work. Let us help you help us! 🎉 -->

## Fixes

<!-- Add the relevant issue number after the word "Fixes" mentioned above (for ex: `## Fixes #0000`) which will automatically close the issue once the PR is merged. -->

<!-- Add a brief overview here of the feature/bug & fix. -->

## PR Type

What kind of change does this PR introduce?

<!-- Please uncomment one or more options below that apply to this PR. -->

<!-- - Bugfix -->
<!-- - Feature -->
<!-- - Code style update (formatting) -->
<!-- - Refactoring (no functional changes, no api changes) -->
<!-- - Build or CI related changes -->
<!-- - Documentation content changes -->
<!-- - Sample app changes -->
<!-- - Other... Please describe: -->

## What is the current behavior?

<!-- Please describe the current behavior that you are modifying, or link to a relevant issue. -->

## What is the new behavior?

<!-- Describe how was this issue resolved or changed? -->

## PR Checklist

Please check if your PR fulfills the following requirements: <!-- and remove the ones that are not applicable to the current PR -->

- [ ] Tested code with current [supported SDKs](../#supported)
- [ ] New component
  - [ ] Pull Request has been submitted to the documentation repository [instructions](../blob/main/Contributing.md#docs). Link: <!-- docs PR link -->
  - [ ] Added description of major feature to project description for NuGet package (4000 total character limit, so don't push entire description over that)
  - [ ] If control, added to Visual Studio Design project
- [ ] Sample in sample app has been added / updated (for bug fixes / features)
  - [ ] Icon has been created (if new sample) following the [Thumbnail Style Guide and templates](https://github.com/CommunityToolkit/WindowsCommunityToolkit-design-assets)
- [ ] New major technical changes in the toolkit have or will be added to the [Wiki](https://github.com/CommunityToolkit/WindowsCommunityToolkit/wiki) e.g. build changes, source generators, testing infrastructure, sample creation changes, etc...
- [ ] Tests for the changes have been added (for bug fixes / features) (if applicable)
- [ ] Header has been added to all new source files (run _build/UpdateHeaders.bat_)
- [ ] Contains **NO** breaking changes

<!-- If this PR contains a breaking change, please describe the impact and migration path for existing applications below.
Please note that breaking changes are likely to be rejected within minor release cycles or held until major versions. -->

## Other information

<!-- Please add any other information that might be helpful to reviewers. -->
