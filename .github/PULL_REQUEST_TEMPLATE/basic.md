* [ ] `@mention` the BSSw.io editorial board member `@<eb-member-id>` in **Description** above assigned to shepherd your PR.
* [ ] Add the `<issue-id>` in the **Description** above for the associated GitHub Issue.
* [ ] Assign this PR to the EB member `<eb-member-id>`.
* [ ] Assign this PR to the author of the PR `<pr-author-id>`.
* [ ] Add label `content: <content-type>` for the type of contribution.
* [ ] Add to Project `Content Development` (see [content development]).
* [ ] Inspect the content in the `*.md` file(s) as rendered in GitHub for this PR.
* [ ] Add one or more Reviewers.
* [ ] Add [meta-data] to the `*.md` file(s) (set `Publish: preview`).
* [ ] Add label `preview` (so PR branch will be merged to 'preview' branch and watch for possible merge failures).
* [ ] Rebuild [preview] site and confirm new content is there, renders correctly and is returned in searches.
* [ ] Make any final changes to the PR based on feedback.
* [ ] Rebuild [preview] site and re-confirm content looks correct.
* [ ] Ensure at least one reviewer signs off on the final changes.
* [ ] Change meta-data to `Publish: yes` and commit if fully ready to publish.
* [ ] Merge this PR (but keep PR in "Item Review" in [content development]).
* [ ] Verify new contribution shows up on [bssw.io] as expected.
* [ ] Move this PR from "Item Review" to "Done".

[preview]: https://preview.bssw.io
[bssw.io]: https://bssw.io
[content development]: https://github.com/betterscientificsoftware/bssw.io/projects/3?
[meta-data]: https://betterscientificsoftware.github.io/bssw.io/bssw_styling_common.html#metadata-section
[wikize_refs.py]: https://github.com/betterscientificsoftware/bssw.io/blob/master/utils/README.md#wikize_refspy
