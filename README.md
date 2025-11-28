# MLtracer

Make machine learning transparent: watch models learn, see the math, ask questions.

---

## 🚀 Overview

MLtracer is an interactive web platform that demystifies machine learning for learners. Upload a dataset, pick an algorithm (Decision Tree, Linear Regression, Naïve Bayes), and watch the model train step-by-step. Every calculation is exposed—entropy, information gain, gradient descent updates, probability updates—with clear formulas, substitutions, and visualizations. An integrated conversational tutor answers “why” and “how” questions in plain language.

---

## 📌 Problem Statement

Machine learning is everywhere, yet for many learners it remains a black box. Libraries like scikit-learn automate training but hide the mathematical steps and intuition behind each operation. Students often struggle to connect theoretical formulas to what happens in practice. There is a need for an educational tool that reveals every calculation and decision a model makes.

---

## 💡 Solution

MLtracer bridges that gap by combining:

* Step-by-step training visualizations (showing intermediate calculations),

* Mathematical breakdowns with formula → substitution → simplification,

* Interactive prediction trace (see how a new sample yields a prediction),

* Side-by-side algorithm comparison (run multiple algorithms on the same dataset),

* Conversational AI Tutor that explains concepts in simple terms and answers user questions.

---

## ⭐ Key Features

Upload CSV datasets and inspect them (summary, missing data, types).

Select algorithm(s): Decision Tree, Logistic / Linear Regression, Naïve Bayes, k-NN, etc.

Training playback: step through iterations (e.g., gradient descent epochs), node splits (decision trees), probability updates (Naïve Bayes).

Live math view: formulas rendered with LaTeX, stepwise substitutions and simplifications for each calculation.

Prediction trace: provide a new sample and see exactly how the model computes the output.

Compare mode: train multiple models on the same data and compare decisions, metrics, and internals.

Interactive visualizations: decision trees, loss curves, feature contributions, confusion matrices.

AI Chatbot Tutor: ask "Why was this split chosen?" or "What does entropy mean here?" and get plain-language answers.

Educational notes and references for each algorithm step.

---
