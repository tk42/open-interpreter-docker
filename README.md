# Open Interpreter Docker
 1. Prepare your OPENAI_API_KEY in `.env`
    ```
    OPENAI_API_KEY=(YOUR_API_KEY)
    ```

 2. Start
    ```
    $ docker-compose up -d
    ```

 3. Access the container
    ```
    $ docker-compose exec interpreter bash
    ```

 4. Run the interpreter
    ```
    ~# interpreter
    ▌ Model set to GPT-4

    Tip: To run locally, use interpreter --local

    Open Interpreter will require approval before running code. Use interpreter -y to bypass this.

    Press CTRL-C to exit.

    > (YOUR PROMPT)
    ```
