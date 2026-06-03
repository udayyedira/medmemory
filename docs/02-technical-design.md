# Technical Design Document

Version: 1.0

## Architecture

Frontend

Next.js

Backend

FastAPI

Database

PostgreSQL

Storage

AWS S3

OCR

Azure Document Intelligence

AI

OpenAI

Authentication

Clerk

Payments

Razorpay

## High Level Flow

User Uploads File

↓

AWS S3

↓

OCR Extraction

↓

LLM Extraction

↓

Review Screen

↓

Database

↓

Timeline Generation

## Environments

### Local

Developer machine

### Staging

Testing environment

### Production

Live environment

## Hosting

Frontend

Vercel

Backend

AWS EC2

Database

AWS RDS PostgreSQL

Storage

AWS S3

## Monitoring

Sentry

Application Logs

Audit Logs

## Security

HTTPS

Encrypted Storage

Signed URLs

Role Based Access Control

Audit Logging

## Backup Strategy

Database Backup Daily

File Backup Daily

Retention 30 Days
