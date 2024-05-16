# FLEXIBLE ZERO-SHOT MUSIC STYLE TRANSFER VIA CLOSING THE LOOP OF LLM-BASED ANALYSIS AND GENERATION

We introduce a versatile zero-shot music style transfer system that leverages the generalizability of large language models (LLMs) for music style analysis and generation. Our method begins by analyzing a music piece using a music understanding LLM, MU-LLaMA, which extracts a text description, and traditional music information retrieval tools to estimate musical contents. With an arbitrary text-based style-transfer command, we employ GPT-4, enhanced through prompt engineering, to adjust these descriptions towards the desired style. These revised descriptions are then input into a novel music generation model, Coco-Mulla, designed to generate music based on textual and content-based controls. 

## Style-Transfer Demo Audio

[Original](demo_audio/Alone/Original.wav) style-transfer command: "Add some acoustic instruments." [Baseline1: MusicGen](demo_audio/Alone/MusicGen.wav) [Baseline2: Coco-Mulla](demo_audio/Alone/V1.wav) [Our Model](demo_audio/Alone/V2.wav)

[Original](demo_audio/Layla/Original.wav) style-transfer command: "A piece that sounds Futuristic." [Baseline1: MusicGen](demo_audio/Layla/MusicGen.wav) [Baseline2: Coco-Mulla](demo_audio/Layla/V1.wav) [Our Model](demo_audio/Layla/V2.wav)

[Original](demo_audio/Never-Gonna-Give-You-Up/Original.wav) style-transfer command: "A pop piece that sounds epic and orchestral." [Baseline1: MusicGen](demo_audio/Never-Gonna-Give-You-Up/MusicGen.wav) [Baseline2: Coco-Mulla](demo_audio/Never-Gonna-Give-You-Up/V1.wav) [Our Model](demo_audio/Never-Gonna-Give-You-Up/V2.wav)

[Original](demo_audio/Smurf/Original.wav) style-transfer command: "A country song with acoustic guitars." [Baseline1: MusicGen](demo_audio/Smurf/MusicGen.wav) [Baseline2: Coco-Mulla](demo_audio/Smurf/V1.wav) [Our Model](demo_audio/Smurf/V2.wav)

[Original](demo_audio/yyw/Original.wav) style-transfer command: "A cheerful EDM." [Baseline1: MusicGen](demo_audio/yyw/MusicGen.wav) [Baseline2: Coco-Mulla](demo_audio/yyw/V1.wav) [Our Model](demo_audio/yyw/V2.wav)
