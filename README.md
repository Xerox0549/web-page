# DevOps Engineer Portfolio

A modern, responsive portfolio website showcasing my DevOps and Cloud Engineering expertise. Built with clean HTML, CSS, and JavaScript, featuring smooth animations, mobile-first design, and integrated contact functionality.

## 🚀 Live Demo

**[View Live Portfolio](https://pushpendra-singh1176.github.io/My-porfolio/)**

## 📋 Overview

This portfolio demonstrates my experience in DevOps, Cloud Infrastructure, and automation technologies. It features a clean, professional design with detailed project showcases, technical skills breakdown, and an integrated contact system.

### Key Highlights
- **3+ Featured Projects** including Kubernetes deployments and CI/CD automation
- **Comprehensive Tech Stack** covering Docker, Kubernetes, AWS, Terraform, and more
- **Professional Contact System** with EmailJS integration
- **Mobile-First Responsive Design** optimized for all devices
- **Smooth Animations** and modern UI/UX patterns

## 🛠️ Tech Stack

### Frontend
- **HTML5** - Semantic markup and accessibility
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)** - Interactive functionality and form handling
- **EmailJS** - Contact form email delivery

### Design & UX
- **Responsive Design** - Mobile-first approach
- **CSS Animations** - Smooth transitions and hover effects
- **Dark Theme** - Professional color scheme
- **Typography** - Inter font family for readability

### Tools & Services
- **Git** - Version control
- **GitHub Pages** - Hosting and deployment
- **EmailJS** - Contact form backend
- **Simple Icons CDN** - Technology icons

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with responsive design
├── script.js           # JavaScript functionality
├── images/             # Project icons and assets
│   ├── Profile.jpeg    # Profile photo
│   ├── aws.svg         # AWS icon
│   ├── terraform.svg   # Terraform icon
│   └── ...            # Other technology icons
├── Pushpendra-singh-Devops.pdf  # Resume/CV
└── README.md          # Project documentation
```

## 🚀 Installation & Usage

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Git (for cloning)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/pushpendra-singh1176/My-porfolio.git
   cd My-porfolio
   ```

2. **Open in browser**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Using Python server
   python -m http.server 8000
   # Then visit http://localhost:8000
   
   # Option 3: Using Node.js server
   npx serve .
   ```

3. **For EmailJS Integration** (Optional)
   - Sign up at [EmailJS](https://www.emailjs.com)
   - Create email service and template
   - Replace credentials in `script.js`:
     ```javascript
     emailjs.init('YOUR_PUBLIC_KEY');
     // Update YOUR_SERVICE_ID and YOUR_TEMPLATE_ID
     ```

## ✨ Features

### 🎯 Core Sections
- **Hero Section** - Professional introduction with animated typing effect
- **About** - Personal background and expertise overview
- **Featured Projects** - Detailed showcase of key DevOps projects
- **Technical Skills** - Comprehensive breakdown of technologies and tools
- **Technologies** - Visual representation of tech stack
- **Contact** - Professional contact form with EmailJS integration

### 🎨 Design Features
- **Responsive Design** - Optimized for desktop, tablet, and mobile
- **Smooth Scrolling** - Enhanced navigation experience
- **Active Section Highlighting** - Navigation shows current section
- **Loading Animations** - Reveal-on-scroll effects
- **Interactive Elements** - Hover effects and button animations
- **Professional Typography** - Clean, readable font hierarchy

### 📱 Mobile Optimization
- **Mobile-First Approach** - Designed for mobile, enhanced for desktop
- **Touch-Friendly Interface** - Proper touch targets and spacing
- **Optimized Performance** - Fast loading and smooth interactions
- **No Horizontal Scrolling** - Proper content containment

### 📧 Contact System
- **EmailJS Integration** - Direct email delivery
- **Form Validation** - Client-side validation with user feedback
- **Success/Error Handling** - Toast notifications for user feedback
- **Professional Email Template** - Structured email format

## 🎯 Featured Projects

### 1. Wanderlust Mega Project (Featured)
- **Technologies**: Docker, Kubernetes, AWS EKS, Terraform, Jenkins, ArgoCD, Prometheus
- **Description**: End-to-end DevOps automation platform with complete CI/CD pipeline
- **Highlights**: GitOps deployment, infrastructure as code, comprehensive monitoring

### 2. Retail Store Sample App (Production Ready)
- **Technologies**: AWS EKS, Terraform, Kubernetes, Docker, ArgoCD, GitHub Actions
- **Description**: Multi-tier microservices application deployed to AWS EKS
- **Highlights**: Production-ready architecture, automated deployment, scalable infrastructure

### 3. Full-Stack Real-Time Chat Application
- **Technologies**: React, Node.js, Express.js, MongoDB, Socket.IO, JWT, Docker
- **Description**: Modern real-time chat application with authentication
- **Highlights**: Real-time messaging, user authentication, containerized deployment

### 4. AWS Infrastructure Automation
- **Technologies**: Terraform, AWS, EKS, VPC, RDS
- **Description**: Modular Terraform infrastructure with CI/CD pipelines
- **Highlights**: Infrastructure as code, multi-environment support, automated deployments

## 📊 Technical Skills Showcase

### Cloud & Infrastructure
- **AWS Services**: EC2, VPC, Security Groups, Load Balancers, S3, IAM, CloudWatch, EKS, RDS, Lambda
- **Infrastructure as Code**: Terraform modules, state management, automation, versioning

### Container & Orchestration
- **Docker**: Multi-stage builds, optimization, networking, volume management
- **Kubernetes**: Deployments, Services, Ingress, ConfigMaps, Secrets, RBAC, monitoring

### CI/CD & Automation
- **Jenkins**: Pipeline automation, GitLab CI integration
- **GitHub Actions**: Workflow automation, deployment pipelines
- **ArgoCD**: GitOps deployments, automated rollbacks

### Monitoring & Observability
- **Prometheus**: Metrics collection, alerting rules
- **Grafana**: Dashboard creation, visualization
- **Logging**: ELK/Loki stack, centralized logging

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Screenshots

### Desktop View
![Desktop Portfolio](https://via.placeholder.com/800x600/0b1220/e6eef6?text=Desktop+Portfolio+View)

### Mobile View
![Mobile Portfolio](https://via.placeholder.com/400x800/0b1220/e6eef6?text=Mobile+Portfolio+View)

### Project Showcase
![Projects Section](https://via.placeholder.com/800x400/0b1220/e6eef6?text=Featured+Projects+Section)

## 🚀 Deployment

### GitHub Pages (Current)
The portfolio is automatically deployed to GitHub Pages from the `main` branch.

**Live URL**: [https://pushpendra-singh1176.github.io/My-porfolio/](https://pushpendra-singh1176.github.io/My-porfolio/)

### Alternative Deployment Options
- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **AWS S3 + CloudFront**: Static website hosting
- **Firebase Hosting**: Google's hosting solution

## 🤝 Contributing

While this is a personal portfolio, suggestions and feedback are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Pushpendra Singh**
- 📧 Email: [pushpendrasingh9942@gmail.com](mailto:pushpendrasingh9942@gmail.com)
- 📱 Phone: [+91 6393780549](tel:+916393780549)
- 📍 Location: Sector 91, Faridabad, Haryana
- 💼 LinkedIn: [pushpendrasingh0549](https://www.linkedin.com/in/pushpendrasingh0549)
- 🐙 GitHub: [pushpendra-singh1176](https://github.com/pushpendra-singh1176)

---

⭐ **If you found this portfolio helpful, please consider giving it a star!**

*Built with ❤️ by Pushpendra Singh*