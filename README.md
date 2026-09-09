Rule-Based Chatbot
A lightweight Python implementation of a rule-based AI chatbot. The chatbot interacts with users via a command-line interface, processing predefined keyword inputs using conditional decision-making logic running inside a continuous interaction loop.

Features
Continuous Interaction Loop: Runs continuously until an exit keyword is entered.

Input Normalization: Strips leading/trailing whitespaces and converts input to lowercase to reliably match user variations.

Rule-Based Decision Logic: Uses standard if-elif-else control flow to deliver specific predefined responses.

Exit Command Handling: Gracefully terminates the session upon receiving designated keywords (exit, quit, bye, goodbye).

Fallback Response: Handles unknown inputs with a helpful default prompt.

Key Skills Demonstrated
Control Flow & Decision-Making: while loops, conditional branching (if, elif, else), and loop termination (break).

Input Sanitization: String manipulation methods (.strip(), .lower()).

Basic AI Concepts: Deterministic rule mapping, intent recognition via keyword presence, and fallbacks.
