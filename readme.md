#Fooocus - Enhanced Version  

### Key Enhancements:  
- Fixed issues with incorrect prompts and seeds during enhance upscale and other enhancement processes.  
- Added functionality for inline LoRA usage, now fully compatible with wildcards. You can use it like this: `<lora:lora_name:1>`.  
  - Also supports LoRA names that include special characters like `(` and Japanese characters.  
- Introduced support for inline aspect ratios, which also work seamlessly with wildcards.  
  - You can specify aspect ratios in the prompt like `1280×720`, `1280x720`, or `1280*720`.  
  - You can also copy-paste them from the available aspect ratios in the Fooocus UI.  
- Improved wildcard processing:  
  - You can now choose to process some wildcards in order while keeping others random, all within the same prompt.  
  - To process a wildcard in order, prefix it with `_o__` instead of `__`.  
  - Specify the starting row for wildcard processing using a suffix, like this: `_o__color__6_` (starts processing from the 6th row).  
  - **Important:** Keep the "process wildcards in order" flag **disabled** in the advanced section.  
- Optimized the skip functionality to avoid using incorrect prompts when skipping generations.  
- Various bug fixes and optimizations for improved performance and stability.  
- Probably more enhancements/bug fixes that I can't remember 😀.  

This version retains Fooocus' simplicity while enhancing its flexibility and accuracy in prompt handling.  

---

### Support My Work  
I’ve been developing and improving Fooocus despite not having a GPU powerful enough to run it myself. If you find this project useful, consider supporting me so I can continue working on it and eventually get better hardware for testing and development.  

☕ [Support me on Ko-fi](https://ko-fi.com/edward_no_genso)  
