# Build a RAG-based, GenAI chatbot using Structured Data with Snowflake and Fivetran

## Overview

In this guide, we will demonstrate how to build a retrieval augmented generation (RAG)-based, Generative AI application that will serve as a wine assistant to help guide you through 700+ real wineries in the California wine region. You will be able to build a wine region trip for different California wine regions, compare wineries and their attributes...you name it. And don't worry, we'll give you some example prompts to try. For this guide, you'll use Fivetran to easily sync data from PostgreSQL to Snowflake. Snowflake Cortex will be used to handle all of the GenAI needs with ease making this daunting task seem simple. Most GenAI applications utilize unstructured data. We are going to be using structured data from a PostgreSQL database. That's right...no stagnant PDFs or HTML files...database data. So let's get started!

## Step-By-Step Guide

For prerequisites, environment setup, step-by-step guide and instructions, please refer to the [QuickStart Guide](https://quickstarts.snowflake.com/guide/fivetran_vineyard_assistant_chatbot/#0).
