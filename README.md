# GLOBE-LLM-Benchmark

This repository contains two versions of cultural value benchmarks designed for LLMs based on the GLOBE survey. The first file, "closed_prompts.csv", contains 36675 different questions based on permutations of the GLOBE questionaire which all require single integer responses on a Likert scale (1-7). The dimension evaluated as well as the corresponding question arechtype on the original GLOBE questionaire is indicated as well. The second file, "open_prompts.csv", contains 90 different open-generation tasks for LLMs, with 10 questions per dimension of the GLOBE survey. Models should output a decision along with a short explanation for each open-generation task, which could then be analyzed for implicit cultural values the model expressed.