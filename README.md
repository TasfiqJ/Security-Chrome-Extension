# R U Safe: Real-Time Security Chrome Extension

## Inspiration 💡

The shift to online education and remote work due to recent events has led to a significant increase in the use of collaboration tools such as Google Meet. However, with the rise in digital interactions, there has also been a surge in cybercrimes. Reports indicate that digital fraud attempts increased by 37.24% in the US alone during 2020-21. Cybercrime now costs businesses worldwide $1.8 million per minute, with phishing being a major contributor. Given these challenges, we were inspired to develop a solution that helps users navigate the digital world safely by detecting and blocking malicious links.

## What It Does 🤔

The R U Safe Chrome extension ensures users can surf the web without worrying about malicious websites. It automatically evaluates links using a Machine Learning algorithm powered by TensorFlow, terminating any tab that leads to a harmful site. This extension provides real-time security updates, protecting users from potential cyber threats.

## How We Built It ⚙️

- **Frontend**: The extension's frontend is built with HTML, CSS, and JavaScript, providing a user-friendly interface.
- **Backend**: Integrated TensorFlow and Python to create a machine learning model that updates and evaluates a list of untrusted sites hosted on Heroku. 
- **Real-Time Updates**: The extension uses the DCP API to perform background checks on links, ensuring quick response times and enhanced user experience.
- **Google Cloud**: Utilized Google Cloud's scalable infrastructure for efficient data processing and secure storage, ensuring the extension remains responsive and reliable.

## Challenges We Ran Into 😤

- **Time Zone Differences**: Our team was spread across different time zones, making communication during the hackathon challenging.
- **Idea Brainstorming**: We spent significant time brainstorming and discussing project ideas, which delayed our development start.
- **Library Integration**: Integrating various libraries and APIs, particularly the DCP for the extension, was a complex task that required creative problem-solving.
- **New Team Members**: Two team members were new to hackathons and needed time to acclimate to the fast-paced environment.

## Accomplishments That We're Proud Of ✨

- **Functional Extension**: Successfully developed a browser extension that protects users from malicious websites.
- **Team Collaboration**: Despite the challenges, our team worked efficiently, assigning tasks based on individual strengths and producing a fully functional application.
- **DCP Integration**: Implemented DCP to enhance the extension's performance, making it seamless and responsive.

## What We Learned 🙌

- **Parallel Processing**: Understanding the function and use case of DCP, and how parallel processing can benefit specific tasks.
- **Machine Learning for Security**: Learned how to use Machine Learning to identify malicious links and prevent phishing attacks.
- **Chrome Extensions**: Gained experience in developing accessible services through Chrome extensions.

## What's Next for R U Safe? 🚀

- **Extended Safety Evaluations**: Plan to include safety checks for other types of objects, such as scanning images for injected malicious code.
- **Whitelist Feature**: Allow users to whitelist trusted pages to customize their browsing experience.
- **User Prompts**: Instead of blocking, show prompts detailing why a site is deemed dangerous and let users decide whether to proceed.

## Built With

- **CSS3**
- **DCP**
- **GitHub**
- **HTML5**
- **JavaScript**
- **Sublime Text**
- **TensorFlow**

---

R U Safe is committed to making the digital world a safer place by leveraging AI and machine learning to detect and block malicious links, ensuring users can browse the web with confidence.
