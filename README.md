# MAIT Quiz: History & Courses

An interactive web-based quiz application that tests users on their knowledge of Maharaja Agrasen Institute of Technology (MAIT) — its history, programs, and campus life. Built with **HTML5**, **CSS3**, and **JavaScript**, this quiz provides instant feedback, a timer per question, randomized questions, and a progress bar, all wrapped in a modern, responsive layout.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Features

- **10 randomized questions** about MAIT’s history and courses
- **Instant feedback** on each answer (Correct/Wrong)
- **30-second timer** per question
- **Progress bar** showing quiz advancement
- **Responsive design** for desktop and mobile
- **Dark teal & coral color scheme** with hover and selection animations
- **Retake option** at the end

## Demo

![Quiz Screenshot](./assets/quiz-screenshot.png)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mait-quiz.git
   cd mait-quiz
   ```
2. **Open** `quiz.html` in your favorite browser.

_No build tools or package managers required — it’s pure front-end!_

## Usage

1. On loading, the quiz will randomize question order.
2. Select an option for each question.
3. Click **Submit** or wait for the timer to expire.
4. View instant feedback and proceed to the next question.
5. After 10 questions, see your final score and **Retake** if you wish.

## Customization

- **Edit questions**: Open `quiz.html` and modify the `questions` array in the `<script>` section.
- **Adjust timer**: Change the `30` seconds default in `startTimer()` and the countdown display.
- **Color scheme**: Tweak CSS variables or hex values in the `<style>` block.

## Development

Feel free to fork this repo and add features like:

- Detailed explanations for each answer
- Admin panel to manage questions via JSON or CSV
- Social sharing for results
- Accessibility enhancements (ARIA labels, keyboard navigation)

## Contributing

1. Fork the repo
2. Create a branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "Add YourFeature"`)
4. Push to branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

Please follow the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/) when contributing.

## License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---
_Powered by MAIT Tech Club_

