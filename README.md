# AI_PMO
An AI-powered Project Management Office (PMO) decision making system

# AI-Powered Project Management Office (AI_PMO)

This repository contains an implementation of an AI-powered Project Management Office (PMO) system. It leverages advanced language models to assist in project planning, decision-making, and team collaboration.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Getting Started](#getting-started)
- [Usage Examples](#usage-examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The AI_PMO system is designed to revolutionize project management by incorporating AI agents into the decision-making process. It simulates team discussions, evaluates project viability, and provides insights based on project data and team dynamics.

## Features

- Project creation and management
- AI-generated team discussions for project evaluation
- Support for multiple project roles with distinct personas
- Integration with advanced language models (Gemini API and LLaMA)
- Customizable project attributes (scope, charter, tasks, cost, deadline)

## System Architecture

The AI_PMO system consists of the following key components:

1. **ProjectRole**: Represents different roles in a project team, each with specific responsibilities and personas.
2. **Project**: Encapsulates all information about a single project.
3. **ProjectManagementSystem**: The main class that ties everything together, managing projects and generating AI-powered discussions.
4. **Language Model Integration**: Utilizes either the Gemini API or LLaMA for generating realistic team discussions.

## Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package manager)

### Installation

1. Clone the repository:
