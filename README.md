This is a little project for chatting with your files.
I personally use this for studying since adding files to chatgpt is sometimes annoying.

I use ollama here because I like hosting my own stuff but you can just exchange it with whatever you want


Gameplan:
    
    Setup chroma and Ollama in Docker  
    Make this it's own docker service ig?
    I need local folder for pdfs

    Ingest PDFs. 
    Save which PDFs already are in DB
    second db for that?
    sounds unneccessary but Idk what else rn
    
    Then just use vdb and communicate with the local model or API

    We are not really searching for specific information that's why this should kinda work okayish ig?

    But then when we ask questions the problem might come up?
    Since it shouldn't be very specific I guess it should be fine? We will see

    Honestly the play might be to just use a high context model and bump up top k in receiver no clue tho without trying
