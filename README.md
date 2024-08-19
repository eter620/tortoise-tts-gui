# tortoise-tts-gui
This is a simple GUI created for the Tortoise-TTS module


The project came about because a friend wanted to make AI voices for his videos but he
thought the current TTS programs were too difficult for him to use. Also he didn't 
want to pay for a service.

This interface works with both the Cuda version and the CPU version of pytorch without needing 
any alterations

instructions:

      1: install pytorch at https://pytorch.org/
      
      2: download tortoise-tts project at https://github.com/neonbjb/tortoise-tts
      
      3: install the tortoise-tts requirements.txt 
      
            a. rename rotary_embedding_torch to rotary-embedding-torch
            
            b. rename progressbar to progresssbar2
            
            c. delete deepspeed==0.8.3, unless you are installing on a linux system
            
            d. rename transformers==4.31.0 to transformers
      
            Note: failure to do the above steps will result in an error
            
      4: install tortoise-tts-gui requirments.txt
      
      5: place tortoise-tts-gui.py into the tortoise-tts-main directory
      
      6: Run tortoise-tts-gui.py from the terminal with: python tortoise-tts-gui.py
