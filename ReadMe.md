### PROJECT TREE
.
├── main
│   ├── java
│   │   └── com
│   │       └── example
│   │           └── DevBlog
│   │               ├── DevBlogApplication.java
│   │               ├── controller
│   │               │   ├── BlogPostController.java
│   │               │   └── CommentController.java
│   │               ├── model
│   │               │   ├── BlogPost.java
│   │               │   ├── Comment.java
│   │               │   ├── Role.java
│   │               │   └── User.java
│   │               ├── repository
│   │               │   ├── BlogPostRepository.java
│   │               │   ├── CommentRepository.java
│   │               │   ├── RoleRepository.java
│   │               │   └── UserRepository.java
│   │               ├── security
│   │               │   ├── CustomUserDetailsService.java
│   │               │   └── WebSecurityConfig.java
│   │               └── service
│   │                   ├── BlogPostService.java
│   │                   ├── CommentService.java
│   │                   ├── RoleService.java
│   │                   └── UserService.java
│   └── resources
│       ├── application.properties
│       ├── static
│       │   └── css
│       │       └── styles.css
│       └── templates
│           ├── blogpost
│           │   ├── create.html
│           │   ├── edit.html
│           │   ├── list.html
│           │   └── view.html
│           ├── comment
│           │   ├── create.html
│           │   └── list.html
│           ├── layout.html
│           └── user
│               ├── edit.html
│               ├── login.html
│               ├── profile.html
│               └── register.html
└── test
└── java
└── com
└── example
└── DevBlog
├── DevBlogApplicationTests.java
├── controller
└── service

25 directories, 31 files