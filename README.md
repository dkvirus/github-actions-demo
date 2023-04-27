# github-actions-demo

- develop: 测试 push 触发, 默认所有分支只要有 push 都会触发
- develop: 修改 push 为 main 分支, 测试 develop 提交代码是否会触发
- main: on 改为 pull-request main 分支, 测试 main 分支 push 代码是否会触发
- develop: 改点内容, 提交一个 pull requests 看是否会触发
- develop: 改为 pull_request_target  main 分支
- develop: 改点内容, 提交一个 pull requests 看是否会触发 pull-request-target