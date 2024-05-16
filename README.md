# FLEXIBLE ZERO-SHOT MUSIC STYLE TRANSFER VIA CLOSING THE LOOP OF LLM-BASED ANALYSIS AND GENERATION

We introduce a versatile zero-shot music style transfer system that leverages the generalizability of large language models (LLMs) for music style analysis and generation. Our method begins by analyzing a music piece using a music understanding LLM, which extracts a stylistic text description, and traditional music information retrieval tools to estimate musical contents. With an arbitrary text-based style-transfer command, we employ GPT-4, enhanced through prompt engineering, to adjust these descriptions towards the desired style. These revised descriptions are then input into a novel music LLM designed to generate music based on textual and content-based controls. 
