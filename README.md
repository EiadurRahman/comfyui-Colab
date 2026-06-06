# Google Colab+ComfyUI Qwen-Image-Edit:   

A python interactive notebook to easily deploy and run ComfyUI on Google Colab, with all settings configured to run the Qwen-Image-Edit model with a custom node to easily manipulate images.

This repository alleviates the pain of manual environment setups, model downloads, and dependency conflicts, providing a one click cell execution environment to get you up and running in minutes.



# Install ComfyUI on Colab

Open Colab & upload the `comfyUI_qwen_image_gguf.ipynb` and connect to a runtime with gpu.

After that the note book will walk you through. 

<img src="assets/noteBOOK.png" alt="ComfyUI on Colab" width="700" />



# run workflow :

Open `qwen_image_edit_workflow.json` on Comfyui and it will probably ready to run

Just upload and image discribe in the prompt and just run

<img src="assets/prompt.png" alt="ComfyUI on Colab" width="700" />

<style>
.compair {
    display: flex;
    flex-wrap: wrap;
    gap: 16px;
    justify-content: center;
    align-items: flex-start;
    background-color: #000000fe;
    color: #fff;
    padding: 16px;
}
.compair__item {
    flex: 1 1 220px;
    min-width: 180px;
    max-width: 33%;
    box-sizing: border-box;
    text-align: center;
}
.compair__item img {
    width: 30%;
    height: auto;
    display: block;
    max-width: 40%;
}

h2 {
    margin-bottom: 8px;
    font-size: 1.5em;
}
@media (max-width: 720px) {
    .compair__item {
        max-width: 100%;
    }
}
</style>
<div class="compair">
    <div class="compair__item">
        <h2>Source</h2>
        <img src="assets/src.png" alt="Before Image">
    </div>
    <div class="compair__item">
        <h2>Output (Qwen-Image)</h2>
        <img src="assets/output_qwen.png" alt="Qwen-Image Output">
    </div>
    <div class="compair__item">
        <h2>Output (Gemini-Image)</h2>
        <img src="assets/output_gemini.png" alt="Gemini-Image Output">
    </div>
</div>