# Sample Video Generation AI Website <JavaScript/Next.JS>

This Next.js application generates videos based on client-provided queries. It is designed as a SaaS platform, allowing users to easily create engaging video content for various purposes such as marketing, education, or social media. The app uses the following technologies to provide a smooth user experience and high-quality video output:

1. NextJs Framework (JavaScript not TS)
2. Clerk Authentication Service
3. Spline 3D Model Asset
4. Tailwind CSS and Shadcn/UI + Sonner
5. Neon Database and Drizzle ORM for Saving files and management of user data
6. Remotion Video to generate videos
7. OpenAI, ElevenLabs, AssemblyAI, & HugginFace API for different services
8. Framer Motion for better UX

---

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/ARYPROGRAMMER/sample-video-generation-website.git
   ```  
3. **Configure the env**:
   ```bash
   # Add the following environment variables to the .env file
   NEXT_PUBLIC_DRIZZLE_DATABASE_URL=
   NEXT_PUBLIC_DRIZZLE_DATABASE_URL=
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_ELEVEN_LABS_API_KEY=
   NEXT_PUBLIC_FIREBASE_API_KEY=
   NEXT_PUBLIC_CAPTION_API=
   NEXT_PUBLIC_OPENAI_API_KEY=

4. **Start the Application**:  
   ```bash  
   npm --legacy-peer-deps i
   npm run dev
   ```  
   The app will be running at [localhost:3000](http://localhost:3000)
   in remote session Linux

5. **WorkSpace Id for Open Hands on (Optional)**:  
   ```bash  
   aryprogrammer-sample-vid-nmuit3803l
   ```
---

## Screenshots

<details>
  <summary>View Screenshots</summary>
  
  <div align="center">
    <img src="screenshots/image%20(1).png" alt="Screenshot 1" width="400px"/>
    <img src="screenshots/image%20(2).png" alt="Screenshot 2" width="400px"/>
    <img src="screenshots/image%20(3).png" alt="Screenshot 3" width="400px"/>
    <img src="screenshots/image%20(4).png" alt="Screenshot 4" width="400px"/>
    <img src="screenshots/image%20(5).png" alt="Screenshot 5" width="400px"/>
    <img src="screenshots/image%20(6).png" alt="Screenshot 6" width="400px"/>
    <img src="screenshots/image%20(7).png" alt="Screenshot 7" width="400px"/>
    <img src="screenshots/image%20(8).png" alt="Screenshot 8" width="400px"/>
    <img src="screenshots/image%20(9).png" alt="Screenshot 9" width="400px"/>
    <img src="screenshots/image%20(10).png" alt="Screenshot 10" width="400px"/>
    <img src="screenshots/image%20(11).png" alt="Screenshot 11" width="400px"/>
    <img src="screenshots/image%20(12).png" alt="Screenshot 12" width="400px"/>
  </div>

</details>

## ✨ Features  

- **AI Video Generation** - Transform text to engaging videos
- **Secure Authentication** - Powered by Clerk Auth
- **Text-to-Speech** - High-quality voice synthesis with Eleven Labs
- **Caption Generation** - Advanced audio processing with Assembly AI
- **Modern UI** - Beautiful interface with shadcn/ui
- **Database** - Robust data handling with Drizzle ORM
- **AI Integration** - GPT-4 and Gemini 15 Flash
