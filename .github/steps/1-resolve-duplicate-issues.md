## Step 1: Resolve duplicate issues

GitHub has special capabilities to help reference other information on GitHub. For example, when you reference another issue or pull request by number, that number will be hyperlinked. At the same time, a cross-reference is created in the linked issue or pull request. This two-way reference helps people track the relationship of information across GitHub.

![a screenshot of an issue linking to a PR, and a PR with a cross-reference to the issue](https://user-images.githubusercontent.com/6351798/172456846-2daec570-08b0-4ffa-a7cb-41acc50b836e.png)

With collaboration from multiple team members, sometimes issues can be duplicated. In the above example, the new issue `#8346` is a duplicate of a previous issue `#8249`. The cross-reference ability allows you to track these duplications and close issues when appropriate.

### Creating references

When you link to another issue, a reference within GitHub is automatically created. In fact, you don't even need to include the full link. If you were to type `#5` within a comment, that would turn into a link to issue or pull request number 5.

When you want to create a crosslink, start typing the title of an issue or pull request directly after you type the `#` symbol. GitHub will suggest issues or pull requests that will link to the right place. To learn even more, check out the [Autolinked References and URLs](https://docs.github.com/en/articles/autolinked-references-and-urls) article.

### :keyboard: Activity: Find and close the cross-linked issue

1. Navigate to the issue #{{duplicate_issue}} (Welcome)
2. Type "Duplicate of #{{original_issue}}" as a comment and close issue #{{duplicate_issue}}
3. After you close the issue, Mona will prepare the next step in this exercise!

