# React Native AsyncStorage: Handling Large Data

This repository demonstrates a common performance issue in React Native when using AsyncStorage to store large JSON objects and offers a solution.

## Problem
Directly storing large JSON objects in AsyncStorage can lead to performance degradation, crashes, and data loss. AsyncStorage is optimized for smaller key-value pairs. Serializing and deserializing large objects can be slow and memory intensive.

## Solution
The solution involves splitting large objects into smaller chunks before storing them in AsyncStorage. This improves performance and reduces the risk of errors.

## Usage
1. Clone the repository.
2. Run `npm install`.
3. Run the project in your preferred React Native environment.
4. Observe the improved performance when storing and retrieving large data.