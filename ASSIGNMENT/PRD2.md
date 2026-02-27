Functional Requirements Document (FRD)

Project Name: BitByBit
Team BitByBit
Fazlul Faizal, Eitan Abrishami, Joshua Delshad, Moh Prajapati, Fotios Bampouridis

1. Introduction
1.1 Purpose

This document outlines the functional requirements for BitByBit, an AI-enhanced e-commerce platform focused on gaming products.

It defines:

System behavior

Core features

User interactions

AI-driven capabilities

This iteration emphasizes an AI-driven architecture, incorporating Groq LLM to provide intelligent search, product discovery, and enhanced customer interaction for all users at no cost.

1.2 Scope

The BitByBit platform facilitates the sale of:

Digital video games

Gaming consoles

Accessories

Gaming merchandise

Key differentiators include:

Robust pre-order management system

Loyalty rewards program

AI-powered deep search

AI-assisted pricing decision-making

AI-enhanced customer support

2. System Overview

BitByBit is a mobile-first AI-enhanced e-commerce application designed for gaming enthusiasts.

Platform Availability:

Web browser (current version)

Android 16+ (testing in progress)

The system enables users to browse, purchase, and interact with gaming products through AI-powered experiences.

3. Functional Requirements

The following requirements are written in “The system shall…” format.

FR-1: AI Search

The system shall allow users to browse the gaming catalog using Groq-powered semantic natural language search.

FR-2: Personalization & AI Insights

The system shall:

Display personalized game recommendations

Provide dynamic pricing

Generate AI-based product review summaries

FR-3: Data Management

The system shall store and manage:

User profile data

Order history

Inventory data

FR-4: Account & Order Management

The system shall allow users to:

Update account details

Modify shopping cart quantities

Track shipping status

Future consideration:

AI-assisted shipment tracking (TBD)

FR-5: Data & Cart Deletion

The system shall allow users to:

Remove items from their cart

Delete saved payment methods

Delete account data

4. Feature Classification
Required Features (Core)

User registration and authentication

Secure shopping cart and checkout

Secure payment processing

Catalog browsing

Order management (via Django backend)

Desired Features (Enhanced)

Groq-powered AI chatbot (24/7 customer support)

AI-powered deep semantic search

Aspirational Features (Future Vision)

AI vision-based return condition analysis

Fully automated dynamic pricing engine

5. Non-Functional Requirements
Usability

The system shall be easy to navigate.

A bottom navigation bar shall assist users in navigation.

Performance

The system shall load user profiles immediately upon login.

Inventory shall be displayed within an acceptable response time.

Security

Payments shall be processed securely.

User profiles and client data shall remain confidential.

Availability

The system shall be available 24/7.

AI support shall operate continuously.

6. System Architecture

The system follows a three-tier architecture:

6.1 Presentation Layer (User Interface)

Built using React Native (JavaScript)

Cross-platform mobile experience

Current primary focus: Android

6.2 Business Logic Layer

Powered by Django (Python 3.x)

Handles:

User authentication (Azure – Work in Progress)

Payment routing

Inventory management

Communication with Groq LLM for AI features

6.3 Data Layer (Database)

MongoDB as the central database

Stores user and product data

Integrated with Azure services

7. Architecture Diagram
