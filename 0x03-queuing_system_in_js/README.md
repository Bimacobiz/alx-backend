# Queuing System in JavaScript

This repository contains the implementation of a queuing system in JavaScript using Redis and Node.js. The project covers various aspects of working with Redis as a queuing system, including basic operations, async operations, advanced operations, and job processing.

## Resources

Read or watch the following resources to get started:

- [Redis Quick Start](https://redis.io/topics/quickstart)
- [Redis Client Interface](https://redis.io/clients)
- [Redis Client for Node.js](https://github.com/NodeRedis/node-redis)
- [Kue - Deprecated but Still Used in the Industry](https://github.com/Automattic/kue)

## Learning Objectives

By the end of this project, you will be able to explain the following concepts without the help of Google:

- Running a Redis server on your machine
- Performing simple operations with the Redis client
- Using a Redis client with Node.js for basic operations
- Storing hash values in Redis
- Dealing with async operations with Redis
- Using Kue as a queue system
- Building a basic Express app interacting with a Redis server
- Building a basic Express app interacting with a Redis server and queue

## Requirements

- All code will be compiled/interpreted on Ubuntu 18.04, Node 12.x, and Redis 5.0.7
- All files should end with a new line
- A `README.md` file at the root of the project folder is mandatory
- Code should use the `.js` extension

## Installation and Setup

Follow these steps to set up the project:

1. **Install Redis:**
   - Download, extract, and compile the latest stable Redis version.
   - Start Redis in the background.
   - Verify that the server is working.

2. **Install Node.js and npm:**
   - Make sure you have Node.js and npm installed on your system.

3. **Install Dependencies:**
   - Run `npm install` to install the required Node.js dependencies.

## Project Structure

The project includes the following files:

- `0-redis_client.js`: Script to connect to the Redis server.
- `1-redis_op.js`: Script for basic Redis client operations.
- `2-redis_op_async.js`: Script for async Redis client operations.
- `4-redis_advanced_op.js`: Script for advanced Redis operations.
- `5-subscriber.js` and `5-publisher.js`: Scripts for Redis publisher and subscriber.
- `6-job_creator.js` and `6-job_processor.js`: Scripts for creating and processing jobs with Kue.
- `7-job_creator.js` and `7-job_processor.js`: Scripts for creating and processing jobs with progress tracking.
- `8-job.js` and `8-job-main.js`: Scripts for creating and testing job creation.
- `9-stock.js`: Express server for managing product stock with Redis.

## Usage

1. **Start Redis Server:**
   ```bash
   $ src/redis-server &

