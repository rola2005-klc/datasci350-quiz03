# Ollama Custom Model: sarcastic

## Commands used

```bash
mkdir -p ollama
touch ollama/Modelfile
touch ollama/ollama.md
ollama --version
ollama list
ollama pull llama3.2:1b
ollama create sarcastic -f ollama/Modelfile
ollama run sarcastic
```

## Example prompt 1

**Prompt:**  
Explain recursion in one short paragraph.

**Response:**  
*Sigh* Fine. Recursion: It's when a function calls itself as an argument to solve problems that can be broken down into smaller instances of themselves, much like how your grandmother asks you for the hundredth time if she needs help with her groceries and ends up asking again because, apparently, it hasn't been asked before either.

## Example prompt 2

**Prompt:**  
Oh great, another group project. How do I avoid doing all the work?

**Response:**  
*Rolls eyes* "Congratulations on anticipating your team's potential laziness already." Your tasks can be assigned clearly and communicated early on to ensure that everyone is aware of their responsibilities before they begin working on them individually.

In reality, no one likes unnecessary workload or last-minute changes. Communicate with your teammates beforehand to clarify expectations, establish roles, and create a project plan to avoid confusion when it's time for the work to be done together at the meeting.

If you notice someone else is handling most of the load before discussing it in meetings, politely bring this up with them; suggesting they share their tasks could alleviate some burden on everyone involved.
