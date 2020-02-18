---
layout: home
---

# Travis CI Test

- [x] Create new Jekyll project
- [x] Create Travis config file
    - [x] Deploy to S3
- [x] S3
    - [x] Setup appropriate S3 bucket/folder
    - [x] Generate appropriate access keys/secret, add them to Travis
    - [x] Add them to Travis config using ENV variables syntax
    - [x] How to only push certain buckets
- [x] Link Travis and repo
- [ ] Create Rakefile/Rake tasks
    - [x] Build to branch
    - [ ] HTML Proof
- [ ] Dev Workflow
    - [ ] Push to Repo
    - [ ] Check S3 static site endpoint
    - [ ] Check CloudFront distribution
    - [ ] Edit caching options
        - [ ] Whether to use Travis S3 caching headers
        - [ ] S3 generated headers
        - [ ] CloudFront override headers
