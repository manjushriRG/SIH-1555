# Smart India Hackathon Workshop
# Date:14/11/2025
## Register Number:212223060150
## Name:Manjushri RG
## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).
## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of Ayush

## Idea
“VR + AI Powered Virtual Herbal Garden for AYUSH Learning”

A highly immersive web platform where users can walk through a 3D herbal garden, interact with 3D medicinal plant models, learn their therapeutic uses, and explore guided tours based on health themes (immunity, skin care, digestion, stress relief, etc.).
The platform uses:

⭐ AI-powered features

Plant Identifier AI: Upload a plant picture → system detects the medicinal plant & shows details.

Personalised Herbal Guide: Users select a health concern → virtual garden suggests relevant AYUSH plants.

AI Narrator: Voice-based guided tours for students.

⭐ Immersive Visual Experience

3D garden walk-through

High-quality 3D models of plants (rotate, zoom, inspect leaves/roots)

Ambient nature sounds + voice explanations

⭐ AYUSH Learning Platform

Detailed plant cards: botanical info, medicinal uses, dosage forms, cultivation

Audio descriptions + videos

Bookmarking, note-taking, and share options

⭐ Gamification

Users earn badges for completing learning modules or exploring themed tours

“Herbal Scholar Score” to motivate student engagement


## Proposed Solution / Architecture Diagram
1️⃣ 3D Virtual Herbal Garden

Built using Three.js / Babylon.js / Unity WebGL

Realistic 3D space with plants arranged by:

Ayurveda

Siddha

Homeopathy

Unani

Each plant can be clicked → opens an interactive info panel

360° rotation, zoom, structural breakdown (leaf, flower, fruit, root)

2️⃣ Herbal Information Repository

Each plant contains:

Botanical Name

Common Names

Habitat

Medicinal Uses

Parts Used

Dosage Forms

Cultivation Methods

Videos, images, audio

Safety Precautions

Stored in PostgreSQL / MongoDB.

3️⃣ Advanced Search & Filters

Search by:

Disease/Condition (e.g., headache, cold, digestion)

Plant type (herb/shrub/tree)

Region (Himalayan, Tropical, Coastal)

System of medicine (Ayurveda, Siddha, Unani)

4️⃣ Virtual Guided Tours

Themes include:

Digestive Health Plants

Immunity Boosters

Skin & Hair Care

Stress Relief & Mental Wellness

Women’s Health

Anti-inflammatory Plants

Tours include narration + animated camera movements + highlighted plants.

5️⃣ User Interaction Layer

Login + profile

Bookmark plants

Add personal notes

Download plant report as PDF

Share plant cards on social media

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/63569856-e7d4-407f-9fea-23aaa5f2e646" />


## Use Cases
Use Case 1 — Student learning about medicinal plants

User logs in

Opens “Immunity Plants Tour”

Watches 3D guided tour with voice narration

Bookmarks Tulsi for later revision

Use Case 2 — Practitioner searching plant details

Searches “Anti-inflammatory plants”

Views Ashwagandha, Turmeric, Neem

Reads cultivation details & dosage

Use Case 3 — Tourist exploring AYUSH knowledge

Enters virtual garden

Walks through 3D herbal zones

Clicks plants to learn their history

Use Case 4 — AI-based Plant Recognition

User uploads a photo of a plant leaf

AI suggests: “This looks like Aloe Vera”

Shows medicinal uses + habitat

Use Case 5 — Researcher generating report

Selects multiple plants

Exports combined details as PDF for academic work


## Technology Stack
Frontend

React.js

Three.js / Babylon.js (3D rendering)

Tailwind CSS / Material UI

Backend

Node.js + Express.js

Database

PostgreSQL (Structured plant data)

MongoDB (optional) for multimedia metadata

3D Models & Assets

Blender (for GLB/GLTF models)

AWS S3 / Cloudinary for hosting

AI Integration

TensorFlow.js / Python Flask microservice

Plant image classification model

Authentication

Firebase Authentication

Maps (Optional)

Google Maps API for showing plant origin regions

Deployment

Vercel / Netlify (frontend)

Render / Railway / AWS EC2 (backend)


## Dependencies

3D model development	1

Database creation & plant data	

Frontend UI and 3D viewer	

Backend API development	

Search & filter system

Guided tours module	
Testing & Deployment

