# auto-commit

Every time the branch is pushed, the `auto-commit` workflow will be triggered.

The workflow will use the `GitHub SHA` as a version to update the `PublishVersion` in app.yaml with message `[ci skip] deploy from <GitHub SHA>`

Note that the commit that update the PublishVersion won't trigger the workflow to run a second time.