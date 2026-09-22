# RG-Care

RG Care Foundation Web Application and Backend API.

## Project Structure

- `backend-ngo-local-main/` — Node.js & Express backend API, database models, email services, and payment gateway integration.
- `ngo-new-main/` — Frontend React web application and static assets.
- `deploy.sh` / `deploy_rgcare.sh` — VPS deployment automation script.

## Getting Started

### Backend Setup
```bash
cd backend-ngo-local-main
npm install
npm run dev
```

### Frontend Setup
```bash
cd ngo-new-main
npm install
npm start
```

## Deployment

Deploy on the VPS using:
```bash
bash deploy.sh
```
