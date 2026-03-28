# CareLink - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69c7fa49a24d40700400e144_user:Mp%40WKQqgqeUoT4vxeJWnUaH9nigxQbsb@ep-curly-boat-ajgq5z71.c-3.us-east-2.aws.neon.tech:5432/AppDB_69c7fa49a24d40700400e144?sslmode=require`

## Web API

**WebApi URL:** https://webapi69c7fa49a24d40700400e144-production.up.railway.app

**Swagger API Tester URL:** https://webapi69c7fa49a24d40700400e144-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
