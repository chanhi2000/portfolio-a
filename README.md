# Portfolio-A

![shield-proj-v][shield-proj-v]
![shield-license-gpl][shield-license-gpl]

## What's included?

![shield-node][shield-node]
![shield-react][shield-react]
![shield-next][shield-next]
![shield-tailwindcss][shield-tailwindcss]

---

# Demo :movie_camera:

![](./public/image/screen.png)

## View live preview [here](https://abusaid.netlify.app/).

---

## :scroll: Table of Contents 

- [Sections](#sections-bookmark)
- [Demo](#demo-movie_camera)
- [Installation](#installation-arrow_down)
- [Getting Started](#getting-started-dart)
- [Usage](#usage-joystick)
- [Packages Used](#packages-used-package)

---

# Sections :bookmark:

- HERO SECTION
- ABOUT ME
- EXPERIENCE
- SKILLS
- PROJECTS
- EDUCATION
- BLOG
- CONTACTS

## 🚀Quickstart

### Build & Run

```sh
npm i;       # install all dependencies
npm run dev; # run locally 
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

# Usage :joystick:

Goto [emailjs.com](https://www.emailjs.com/) and create a new account for the mail sending. In free trial you will get 200 mail per month. After setup `emailjs` account, Please create a new `.env` file from `.env.example` file.

Eg:

```env
NEXT_PUBLIC_EMAILJS_SERVICE_ID =
NEXT_PUBLIC_EMAILJS_TEMPLATE_ID =
NEXT_PUBLIC_EMAILJS_PUBLIC_KEY =
```

### Then, Customize data in the `utils/data` [folder](https://github.com/chanhi2000/portfolio-a/tree/main/utils/data).

Eg:

```js
export const personalData = {
  name: "ABU SAID",
  profile: "/profile.png",
  designation: "Full-Stack Software Developer",
  description: "My name is ABU SAID....",
  email: "abusaid7388@gmail.com",
  phone: "+8801608797655",
  address: "Dhaka, Bangladesh",
  github: "https://github.com/said7388",
  facebook: "https://www.facebook.com/abusaid.riyaz/",
  linkedIn: "https://www.linkedin.com/in/abu-said-bd/",
  twitter: "https://twitter.com/said7388",
  stackOverflow: "https://stackoverflow.com/users/16840768/abu-said",
  leetcode: "https://leetcode.com/said3812/",
  devUsername: "said7388",
  resume: "...",
};
```

`devUsername` Used for fetching blog from `dev.to`.

---

# Packages Used :package:

| Used Package List  |
| :----------------: |
|        next        |
|  @emailjs/browser  |
|    lottie-react    |
| react-fast-marquee |
|    react-icons     |
|   react-toastify   |
|        sass        |
|    tailwindcss     |

---

[shield-proj-v]: https://img.shields.io/github/package-json/v/chanhi2000/crashcourse?style=flat-square
[shield-license-gpl]: https://img.shields.io/aur/license/node?style=flat-square
[shield-node]: https://img.shields.io/badge/node.js-18.12.x-339933?logo=nodedotjs&logoColor=339933&style=flat-square
[shield-react]: https://img.shields.io/badge/react.js-18.2.x-61DAFB?logo=react&logoColor=61DAFB&style=flat-square
[shield-next]: https://img.shields.io/badge/next.js-18.2.x-000000?logo=nextdotjs&logoColor=000000&style=flat-square
[shield-tailwindcss]: https://img.shields.io/badge/next.js-3.3.x-06B6D4?logo=tailwindcss&logoColor=06B6D4&style=flat-square
