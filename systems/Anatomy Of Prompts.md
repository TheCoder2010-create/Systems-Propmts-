 Anatomy of a Good Prompt
Components:
1. Role/Persona
"You are a senior Python developer..."
2. Task/Instruction
"Create a function that..."
3. Context
"This will be used in a web API that handles 1000 requests/sec..."
4. Constraints
"Use only standard library, no external dependencies"
5. Output Format
"Return code with inline comments and docstrings"
6. Examples (Optional)
"Similar to: [example code]"

SLIDE 7: Bad vs Good Prompts
❌ Bad Prompt:
"Make a login system"
Problems:

Too vague
No context
No requirements
No constraints

✅ Good Prompt:
"Create a secure user login API endpoint using Node.js and Firebase Auth.

Requirements:
- Email/password authentication
- Input validation (email format, password min 8 chars)
- Rate limiting: 5 attempts per 15 minutes
- Return JWT token on success
- Handle errors gracefully

Output: Express.js route handler with inline comments"
Why it's better:

Specific technology stack
Clear requirements
Security considerations
Expected output format