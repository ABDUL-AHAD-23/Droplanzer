# Droplanzer 

Droplanzer is a clean and fast Next.js website for creative agencies, studios, and freelancers. 



## Color Reference

| Name                   | Hex       |
| ---------------------- | --------- |
| Background             | #00041f   |
| Foreground             | #ffffff   |
| Primary                | #194eff   |
| Secondary Background   | #6d7791   |
| Dark                   | #00020d   |
| Text Secondary         | #d6d6d6   |
| Accent Green           | #00b48a   |
| Accent Green Light     | #00d1a0   |


## 🧑‍💻 Tech Stack

- Next js
- TailwindCSS
- Gsap/react


## 📑 Prerequisites
- Node.js (v14 or higher)
- Mailtrap account (for email testing)
- Google recaptcha v2 
## ⚙️ Installation
1. Clone the repository
```bash
  git clone <repository-url>
  cd Droplanzer
```

2. Install dependencies

```
npm install

```

3. Environment Setup Create a .env.local file in the root directory with the following variables:

```
# Mailtrap sandbox (testing only). Use production SMTP host in live environment.
SMTP_HOST="gmail.com"  

SMTP_PORT="587"
SMTP_USER="contact.droplanzer@gmail.com"
SMTP_PASS="czcy zpun idrs tlgh"
ADMIN_EMAIL="contact.droplanzer@gmail.com"


NEXT_PUBLIC_RECAPTCHA_SITE_KEY="6LfUNz4sAAAAAHLnof6sLJ_WSm-XHUlb0N21Wg5x"
RECAPTCHA_SECRET_KEY="6LfUNz4sAAAAACp-JFk4miZloKqfm06rAsVqKolx"

```

## 🚀 Running the Application

1. Start the main server

```bash
npm run dev
```

2. If Done Development, Build

```bash
npm run build
```

3. If Done Build

```bash
npm run start
```

## 📚 Dependencies

- "@gsap/react": "^2.1.2",
- "next": "15.4.2",
- "nodemailer": "^7.0.5",
- "react": "19.1.0",
- "react-dom": "19.1.0",
- "react-google-recaptcha": "^3.1.0",
- "react-icons": "^5.5.0",
- "react-zoom-pan-pinch": "^3.7.0",
- "swiper": "^11.2.10"
