---
marp: true
theme: custom-default
footer: 'Sora Director Presentation'
---

# 🎬 Lights, Camera, Algorithm!

![bg right](https://picsum.photos/800/600)

"From Concept to Cinema in Six Simple Tabs"

<!-- Speaker notes: Introduction to Sora Director -->

---

## Key Technologies & Tools Used

### 💻Code Development : Vibe coded using VSCode/Github Copilot (Claude)

---

### 🤖 AI & Machine Learning
- Azure OpenAI Services - Core AI engine for text generation and assistants
- DALL-E 3 & GPT-Image-1 - Advanced image generation and editing
- SORA - Next-generation video generation model
- Azure Cognitive Speech Services - Text-to-speech with SSML support
### 🌐 Web Framework & UI
- FastAPI - High-performance web API framework
- Gradio - Interactive web UI for AI applications
- Jinja2 - Template engine for dynamic content

---

## 
### 🔐 Authentication & Security
- Google OAuth 2.0 - Secure user authentication
- Azure Identity - Enterprise-grade security integration
- Session Management - Encrypted cookie-based sessions


### 🎬 Media Processing
- MoviePy - Video creation and manipulation
- Pillow (PIL) - Image processing and format conversion
- NumPy & SciPy - Audio data processing and manipulation

--- 

### ⚡ Performance & Scalability
- Multiprocessing - Parallel video generation for performance
- Async/Await - Non-blocking operations for responsiveness
- Uvicorn - High-performance ASGI server

### 📊 Data & Configuration
- Python-dotenv - Environment configuration management
- JSON - Data exchange and configuration storage
<!-- Speaker notes: Key features and benefits overview -->

---
## Project Lifecycle

- 🤖 Well this deck itself is partially AI Generated
- 📊 Let's refer to Github [Commit history](https://github.com/sanrawat_microsoft/llm-poc/commits/main/) 

### Or better yet, let's use AI to generate the project timeline 😊

---

## Project Timeline - Major Milestones
### 🚀 Phase 1: Foundation & Core Infrastructure
#### Initial Setup and Basic AI Integration

- Project Initialization: Established FastAPI web framework with modular architecture
- Authentication System: Implemented Google OAuth2 authentication with secure session management
- Azure OpenAI Integration: Connected primary AI services with Azure OpenAI for text generation
- Multi-Tab UI Framework: Built Gradio-based interface with 6 distinct tabs (Agent, Image, Voice, Video, Sora Assistant, Settings)

---
### 🎨 Phase 2: Multimodal AI Capabilities
#### Image and Voice Processing Integration

- Image Generation: Integrated Azure DALL-E 3 for AI image generation with edit capabilities
- Voice Processing: Added bidirectional voice capabilities:
    - Speech-to-text transcription using Azure Speech Services
    - Text-to-speech with advanced SSML support for emotional and multi-language synthesis
- Advanced Voice Features: Implemented 20+ voice options including Indian regional voices
- SSML Template System: Created sophisticated speech markup with emotional controls and pronunciation guides

--- 

### 🎬 Phase 3: Video Generation Revolution
#### SORA API Integration & Advanced Media Processing

- SORA Video Generation: Successfully integrated OpenAI's SORA API for AI video generation
- Multiple Video Formats: Support for various video sizes (1920x1080, 1080x1920, 1280x768) and durations (5-20 seconds)
- Asynchronous Processing: Implemented job-based video generation with real-time progress tracking
- Film Strip Gallery: Created cinematic video display with thumbnail previews and full-screen playback

--- 

### 🔧 Phase 4: Specialized Assistant Architecture
#### Dedicated SORA Assistant & Media Combination

- Sora Assistant Agent: Developed specialized assistant module (sora_assistant_agent.py) with enhanced video generation capabilities
- Multiprocessing Architecture: Solved event loop conflicts using Windows-compatible multiprocessing for video generation
- Media Combination Engine: Built sophisticated media combiner using MoviePy for creating videos from images and audio
- Progress Indicators: Implemented real-time progress bars and status tracking for long-running operations

---

### 📊 Phase 5: Production Readiness
#### Deployment & Configuration Management

- Azure Developer CLI: Configured azure.yaml for streamlined deployment to Azure App Service
- Infrastructure as Code: Created Bicep templates for automated Azure resource provisioning
- Configuration Management: Built comprehensive settings panel for runtime configuration of all services
- Error Handling: Implemented robust error handling and logging throughout the application
#### 🎯 Current State: Full-Stack AI Application

---

## Demo Time

![center](https://localhost:8000/)

**Let's see Sora Director in action!**

<!-- Speaker notes: Live demonstration of the platform -->

---

## References
- [Demo](https://sanrawat-llm-fgb9c2bqavf9fjdd.centralindia-01.azurewebsites.net/)
- Code : https://github.com/sanrawat_microsoft/llm-poc
- Deck : https://sandeeprawat.github.io/decks/soradirector.html


---

# Thank You

**Questions & Discussion**

![bg right](https://picsum.photos/800/600)

---

Visit us at: **microsoft.com**
Follow us: **@microsoft**

<!-- Speaker notes: Contact information and next steps -->
