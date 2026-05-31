# Hi, I'm Amine
Software engineering student at FST-Settat (Hassan 1er University), mostly working on backend systems and distributed architecture.

## About me
I got into programming through Unity and C#, then more formally through C — data structures, memory management, system calls. C is capricious, but spending enough time with it leaves marks: it shaped how I think about what a program actually does, and it's what pulled me toward backend work and systems design when I moved to higher-level languages.

Today I mostly work in Java with Spring Boot, digging into new parts of the framework while building things that actually run. Lately I've also been getting into mobile development through Flutter — chasing performance on constrained hardware scratches the same itch.

## Projects

### [Sprout](https://github.com/AmineSidki/Sprout)
A CLI tool that scaffolds Spring Boot boilerplate from your JPA `@Entity` classes: repositories, services, DTOs (as Java records), MapStruct mappers, REST controllers, and exception classes. Parses source with **JavaParser** (AST-based, no reflection), renders output through **Mustache.java** templates, and ships as a zero-dependency binary via **Homebrew** (macOS/Linux) and **Scoop** (Windows).

Built with Picocli, packaged with JReleaser.

### [DeepDame](https://github.com/abdellah-darni/DeepDame)
A real-time multiplayer checkers platform with friend invites, random matchmaking, and a single-player mode against a game engine. Built on Spring Boot with WebSocket/STOMP, a polyglot persistence layer (PostgreSQL, MongoDB, Redis), and a Flutter client. Redis pub/sub enables horizontal scaling across instances; load-tested with **k6** to **3,000 concurrent users** and deployed on EKS.

### [PostPrep](https://github.com/AmineSidki/PostPrep-Backend)
A document processing tool that extracts structured metadata from PDFs or raw text: title, summary, keywords, categories, language, and SEO title. Runs **Tesseract OCR** on scanned documents, feeds extracted text to **Mistral-7B-Instruct** via the HuggingFace Inference API, and validates output with a cosine similarity hallucination check against the source content. Frontend in React + TypeScript + Tailwind; backend live on Hugging Face Spaces.

## Stack
**Languages:** C · Java · Python · Dart · JavaScript · HTML/CSS  
**Frameworks:** Spring Boot · Flutter · React · Bootstrap · Tailwind CSS  
**Infrastructure:** PostgreSQL · MySQL · Redis · MinIO · Docker · Docker Compose · GitHub Actions · Git · Bash

[![Read more on my blog](assets/button.svg)](https://aminesidki-blog.vercel.app/)
