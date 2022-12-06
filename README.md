# springboot-best-practices


Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS E:\Microservices projects\2022 projects\springboot-best-practices> git init
Reinitialized existing Git repository in E:/Microservices projects/2022 projects/springboot-best-practices/.git/
PS E:\Microservices projects\2022 projects\springboot-best-practices> git init -b main
warning: re-init: ignored --initial-branch=main
Reinitialized existing Git repository in E:/Microservices projects/2022 projects/springboot-best-practices/.git/
PS E:\Microservices projects\2022 projects\springboot-best-practices> git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
add
PS E:\Microservices projects\2022 projects\springboot-best-practices> git add .
PS E:\Microservices projects\2022 projects\springboot-best-practices> git commit -m "initial commit"
[main d49cf24] initial commit
28 files changed, 108 insertions(+)
create mode 100644 .idea/.gitignore
create mode 100644 .idea/compiler.xml
create mode 100644 .idea/encodings.xml
create mode 100644 .idea/jarRepositories.xml
create mode 100644 .idea/jpa-buddy.xml
create mode 100644 .idea/misc.xml
create mode 100644 .idea/vcs.xml
create mode 100644 target/classes/application.properties
create mode 100644 target/classes/application.yml
create mode 100644 target/classes/com/javatechie/ProductServiceApplication.class
create mode 100644 target/classes/com/javatechie/config/BatchConfig.class
create mode 100644 target/classes/com/javatechie/config/EmailConfig.class
create mode 100644 target/classes/com/javatechie/config/MessagingConfig.class
create mode 100644 target/classes/com/javatechie/config/SecurityConfig.class
create mode 100644 target/classes/com/javatechie/controller/ProductController.class
create mode 100644 target/classes/com/javatechie/dto/APIResponse$APIResponseBuilder.class
create mode 100644 target/classes/com/javatechie/dto/APIResponse.class
create mode 100644 target/classes/com/javatechie/dto/ErrorDTO.class
create mode 100644 target/classes/com/javatechie/dto/ProductRequestDTO.class
create mode 100644 target/classes/com/javatechie/dto/ProductResponseDTO.class
create mode 100644 target/classes/com/javatechie/entity/Product.class
create mode 100644 target/classes/com/javatechie/exception/ProductNotFoundException.class
create mode 100644 target/classes/com/javatechie/exception/ProductServiceBusinessException.class
create mode 100644 target/classes/com/javatechie/handler/ProductServiceExceptionHandler.class
create mode 100644 target/classes/com/javatechie/repository/ProductRepository.class
create mode 100644 target/classes/com/javatechie/service/ProductService.class
create mode 100644 target/classes/com/javatechie/util/ValueMapper.class
create mode 100644 target/classes/com/jt/demo/CommonUtils.class
PS E:\Microservices projects\2022 projects\springboot-best-practices> git remote add origin main
error: remote origin already exists.
PS E:\Microservices projects\2022 projects\springboot-best-practices> echo "# springboot-realtime" >> README.md
PS E:\Microservices projects\2022 projects\springboot-best-practices> git init
Reinitialized existing Git repository in E:/Microservices projects/2022 projects/springboot-best-practices/.git/
PS E:\Microservices projects\2022 projects\springboot-best-practices> git add README.md
PS E:\Microservices projects\2022 projects\springboot-best-practices> git commit -m "first commit"
[main 9e0b89d] first commit
1 file changed, 0 insertions(+), 0 deletions(-)
PS E:\Microservices projects\2022 projects\springboot-best-practices> git branch -M main
PS E:\Microservices projects\2022 projects\springboot-best-practices> git remote add origin https://github.com/rajapalai/springboot-realtime.git
error: remote origin already exists.
PS E:\Microservices projects\2022 projects\springboot-best-practices> git push -u origin main
remote: Permission to Java-Techie-jt/springboot-best-practices.git denied to rajapalai.
fatal: unable to access 'https://github.com/Java-Techie-jt/springboot-best-practices.git/': The requested URL returned error: 403
PS E:\Microservices projects\2022 projects\springboot-best-practices> git remote add origin https://github.com/rajapalai/springboot-realtime.git
error: remote origin already exists.
PS E:\Microservices projects\2022 projects\springboot-best-practices> git branch -M main
PS E:\Microservices projects\2022 projects\springboot-best-practices> git push -u origin main
remote: Permission to Java-Techie-jt/springboot-best-practices.git denied to rajapalai.
fatal: unable to access 'https://github.com/Java-Techie-jt/springboot-best-practices.git/': The requested URL returned error: 403
PS E:\Microservices projects\2022 projects\springboot-best-practices> git logout
git: 'logout' is not a git command. See 'git --help'.
PS E:\Microservices projects\2022 projects\springboot-best-practices> git init
Reinitialized existing Git repository in E:/Microservices projects/2022 projects/springboot-best-practices/.git/
PS E:\Microservices projects\2022 projects\springboot-best-practices> git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
(use "git push" to publish your local commits)

nothing to commit, working tree clean
PS E:\Microservices projects\2022 projects\springboot-best-practices> git remote -v
origin  https://github.com/Java-Techie-jt/springboot-best-practices.git (fetch)
origin  https://github.com/Java-Techie-jt/springboot-best-practices.git (push)
PS E:\Microservices projects\2022 projects\springboot-best-practices> git remote set url https://github.com/rajapalai/springboot-realtime.git
error: unknown subcommand: `set'
Counting objects: 100% (111/111), done.
Delta compression using up to 4 threads
Compressing objects: 100% (86/86), done.
Writing objects: 100% (111/111), 35.07 KiB | 3.51 MiB/s, done.
Total 111 (delta 18), reused 44 (delta 5), pack-reused 0
remote: Resolving deltas: 100% (18/18), done.
To https://github.com/rajapalai/springboot-realtime.git
* [new branch]      main -> main
  branch 'main' set up to track 'origin/main'.
  PS E:\Microservices projects\2022 projects\springboot-best-practices>
