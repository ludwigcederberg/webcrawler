# Multithreaded Web Crawler

## Project Overview

This project is a **Java-based multithreaded web crawler** designed to scrape and store content from multiple URLs concurrently. I developed this as part of my Computer Science studies to apply concepts of concurrency, object-oriented design, and file handling in a real-world setting.

## Skills and Technologies

- **Concurrent Programming**: Leveraged Java's concurrency utilities to manage multiple threads, implementing synchronization for safe access to shared resources like the URL queue.
- **Object-Oriented Design**: Structured the project with classes like `URLQueue`, `CrawlerWorker`, and `ContentStorage`, ensuring modular, organized, and extendable code.
- **Data Storage**: Used file I/O to store webpage content, implementing basic error handling for network requests with `HttpURLConnection`.

## Key Learnings

This project taught me essential skills in:

- **Thread Safety**: Developing solutions for thread-safe URL tracking and queue management.
- **Error Handling**: Handling unpredictable issues like broken links and unreachable URLs.
- **Design and Organization**: Creating a clear, modular structure that made the project easier to debug and extend.

## Future Enhancements

Next steps include adding HTML parsing for targeted data extraction, expanding storage options to a database, and refining thread efficiency with advanced scheduling.

---

Building this project was a great learning experience in multithreaded programming, and I’m excited to keep enhancing it!
