# Blueprint

Blueprint is a microservice development toolchain that enables rapid Configure, Build, Deploy pattern for generating microservice applications. With just a few lines of code, users can easily reconfigure an application’s design; Blueprint will then generate a fully-functioning variant of the application under the new design. Blueprint introduces flexible zero-cost abstractions for developing applications that enforce a strict separation of concerns between application-level logic, lower-level infrastructure components, and implementation and configuration choices. Blueprint is open-source and extensible; it supports a wide variety of reconfigurable design dimensions; and we have ported all major microservice benchmarks to it. Our evaluation demonstrates how Blueprint simplifies the three core use-cases with orders-of-magnitude less code change.

## Availability

THe official release of Blueprint is coming soon. Once released, Blueprint will be available [here](https://github.com/Blueprint-uServices/blueprint).

In the meantime, please join our mailing group [here](https://groups.google.com/g/blueprint-compiler).

## Publications

+ Blueprint: A Toolchain for Highly-Reconfigurable Microservice Applications, SOSP'23. [Paper](https://dl.acm.org/doi/10.1145/3600006.3613138), [Paper + Appendix](https://vaastavanand.com/assets/pdf/anand2023blueprint.pdf), [Artifact](https://gitlab.mpi-sws.org/cld/blueprint/blueprint-sosp23-experiments)

## Contributing to Website

Step 1: Fork this repo
Step 2: Add necessary markdown files.
Step 3: Create a Merge Request

+ New Tutorial: Create a markdown file in the folder ```_posts```
+ New Blog Post: Create a markdown file in the folder ```_blogposts```
+ New Documentation Page: Create a markdown file in the folder ```_documents```

## Deploying Website

### Local deployment (launches on http://localhost:4000):

```bash
bundle exec jekyll serve
```

### Global deployment

```bash
./bin/deploy
```
