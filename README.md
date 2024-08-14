# Frontend Technical Test

## Test Description:

Develop a small web application using Next.js, Tailwind CSS, and TypeScript that displays the transcription of a phone call in a component mapping each message from both the agent and the user. The application should allow the user to click on any part of the transcript and automatically jump to that specific part of the audio.

### Technical Requirements:

#### Frontend:
- Use Next.js as the React framework.
- Implement the user interface using Tailwind CSS.
- Use TypeScript to enhance code quality and readability.

#### Transcription Component:
- Create a component that maps each message (both from the agent and the user) in the call transcription.

#### Functionality:
- Display the call transcription in a component with separate messages for the agent and the user.
- Play the call audio.
- Allow the user to click on any part of the transcription to jump to that part of the audio.
- Provide basic audio playback controls (play, pause, stop).

### Additional Points (Optional):

#### Responsive Design:
- Make the application fully responsive to adapt to different screen sizes.

#### Styling and Animations:
- Use Tailwind CSS to style the application and add smooth animations to enhance user experience.

> **Note:** Remember to maintain a modular and scalable approach in your code.
> Code clarity, readability, and efficiency will be considered in the evaluation.
> Good luck and have fun!

### Transcription Reference:
[
 {
 "content": "¡Hola! Soy Rocio, asesora de admisiones de la Universidad Online. ¿En qué puedo ayudarte hoy?",
 "role": "agent",
 "start": 1.005,
 "end": 6.331625
 },
 {
 "content": "Hola Rocio, ¿cómo estás? Estoy interesado en las licenciaturas relacionadas con tecnología.",
 "role": "user",
 "start": 7.24,
 "end": 15.562688
 },
 ...
]


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
