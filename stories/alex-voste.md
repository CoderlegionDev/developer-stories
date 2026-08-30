# Fighting Build-System Complexity: Alex Voste on Systems Programming, Performance and ForgeZero

> **CoderLegion Developer Story**

Alex Voste is a Canada-based systems-focused developer working across C, Go, x86_64 Assembly, C++, Linux, performance optimization, and developer tooling.

His work is driven by a fascination with what happens underneath software abstractions — including memory, computer architecture, compilers, build systems, and execution performance.

Alex is currently building **ForgeZero**, a cross-platform build toolchain for C and Assembly developers.

---

## From Web Development to Systems Engineering

Alex began his career working with PHP and later Java and backend development.

Over time, he became increasingly interested in what happens underneath application-level abstractions: how programming languages work, how systems manage memory, and how software interacts with hardware.

That interest eventually led him toward systems programming, Linux, C, Assembly, performance optimization, and developer tooling.

ForgeZero began as a personal project while Alex and a friend were experimenting with building an operating system in Assembly.

---

## Why Build ForgeZero?

Alex wanted a build toolchain that gave developers more control over what was actually happening during a build.

His experience with low-level development made him uncomfortable with tooling that hides too much complexity or performs work developers did not explicitly request.

ForgeZero was created around a simple philosophy:

> If I didn't type it, it shouldn't be running.

The project focuses on speed, control, simplicity, security, and minimizing unnecessary overhead.

---

## What Alex Thinks Modern Build Systems Get Wrong

Alex believes many modern build systems perform more work than necessary because they attempt to support a huge range of scenarios and platforms.

His approach is deliberately different: keep the architecture lean, reduce unnecessary operations, and let developers maintain control over their build process.

For Alex, simplicity is not merely about having less code. It is about avoiding unnecessary work and making system behavior easier to understand.

---

## Why Go and Assembly?

Go became the foundation for ForgeZero because Alex sees it as a practical balance between simplicity, safety, and performance.

Assembly still has an important role in the project, particularly on performance-critical paths.

His approach is to use low-level techniques deliberately where they provide meaningful performance benefits while maintaining control over the boundaries where additional complexity and risk are introduced.

---

## Where Does the Performance Come From?

Alex attributes ForgeZero's performance philosophy primarily to architectural simplicity.

Instead of maintaining unnecessary abstractions, allocations, or state, the project attempts to perform fewer operations and execute the necessary work efficiently.

The underlying idea is straightforward:

**Don't spend CPU cycles on work the developer doesn't need.**

---

## Control vs. Convenience

Alex believes low-level developers often value control more than convenience.

Systems programmers working with C, Assembly, and hardware-oriented software may want to understand what their tools are doing instead of having everything hidden behind layers of abstraction.

For Alex, good developer tooling should stay out of the way and give engineers control over their environment.

---

## Open Source and Building in Public

Open source is an important part of Alex's approach to software development.

He believes fundamental developer tooling should remain accessible to the community.

Building in public also creates accountability. When the code and architecture are visible to others, developers have an additional reason to keep their work understandable and maintainable.

---

## Performance vs. Complexity

Alex is highly focused on performance, but he also recognizes that optimization can introduce unnecessary complexity.

His practical test is whether an optimization produces meaningful real-world benefits.

Saving a developer time on every build can accumulate into significant productivity gains.

On the other hand, adding substantial complexity for an optimization that has no meaningful practical impact can become what he describes as **vanity engineering**.

The important distinction is measuring real-world impact rather than optimizing purely for impressive benchmark numbers.

---

## AI and Low-Level Engineering

Alex is skeptical that AI will completely replace the need for deep systems-programming knowledge.

In his experience, AI assistants can be useful for documentation, explanations, and certain programming tasks, but low-level engineering requires a deeper understanding of memory, hardware, architecture, and system constraints.

He also describes an experience where an AI-assisted attempt at a low-level networking project produced enough incorrect output and memory-handling problems that he ultimately found it faster to write the implementation himself.

His conclusion is that developers working close to the hardware will still need strong fundamentals, particularly in C, Assembly, and computer architecture.

---

## What's Next for ForgeZero?

Alex's immediate goal is to build a team of developers interested in systems programming and improving developer tooling.

He wants ForgeZero to remain free, fast, and useful to developers working close to the hardware.

He is also exploring how lightweight AI could eventually be used for specific tasks such as build-graph optimization, while avoiding AI being added simply as a marketing feature.

---

## The Engineer Behind the Optimization

Alex's interest in performance comes from a refusal to accept unnecessary limitations.

When he sees a process consuming resources without a clear reason, he wants to understand where the overhead comes from and whether it can be removed.

That mindset has shaped both his systems-programming work and ForgeZero.

His approach can be summarized as:

**Understand the system. Measure the cost. Remove unnecessary work.**

---

## Key Takeaways

Alex's story highlights several lessons for developers:

- Career paths in software don't have to be linear.
- Understanding systems underneath abstractions can open new areas of engineering.
- Build tooling has a major impact on developer productivity.
- Simplicity can be a powerful performance strategy.
- Low-level programming requires strong fundamentals.
- Performance optimizations should be measured against real-world impact.
- Open-source development can help keep engineering work transparent.
- AI can assist developers, but deep technical understanding remains important.
- Developers working with AI-generated code still need to understand the systems underneath it.

---

## About Alex Voste

Alex's technical interests include:

- C
- Go
- C++
- x86_64 Assembly
- NASM
- FASM
- Linux
- Node.js
- Performance optimization
- Linkers
- Developer tooling

He is currently building **ForgeZero**, a build toolchain for Assembly and C developers.

### ForgeZero

GitHub: https://github.com/forgezero-cli/forgezero

### CoderLegion Profile

https://coderlegion.com/user/alexvoste

---

## Read the Full Developer Story

This GitHub version is a curated edition of the original CoderLegion Developer Story.

**Read the full interview on CoderLegion:**

https://coderlegion.com/25614/fighting-build-system-complexity-alex-voste-systems-programming-performance-forgezero

---

## About CoderLegion

CoderLegion is a community built for developers to share knowledge, connect with other developers, discover developer stories, join discussions, explore jobs, and build their developer presence.

https://coderlegion.com
