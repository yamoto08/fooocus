# Fooocus - Enhanced Version

### Key Enhancements:
- Fixed issues with incorrect prompts and seeds during enhance upscale and other enhancement processes.
- Added functionality for inline LoRA usage, now fully compatible with wildcards you can use it like this: `<lora:lora_name:1>`
- also supports loras names which have special characters like ( and japanese characters.
- Introduced support for inline aspect ratios, which also work seamlessly with wildcards, type in the prompt the aspect ratio like this 1280×720 or 1280x720 or 1280*720, you can also copy paste it from the available aspect ratios in Fooocus User interface.
- Improved wildcard processing: You can now choose to process some wildcards in order while keeping others random, all within the same prompt, to process a wildcard in order prefix it with: _o__ instead of __ 
- Added the ability to specify the starting row for wildcard processing, decide the starting row by using a suffix like this: __6_ will start processing from the 6th row in the wildcard _o__color__6_, please don't change the process "wildcards in order" flag in the advanced section (keep it disabled)
- Optimized the skip functionality to avoid using incorrect prompts when skipping generations.
- Various bug fixes and optimizations for improved performance and stability.
-Probably more enhancements/ bug fixes that I can't remember 😀.

This version retains Fooocus' simplicity while enhancing its flexibility and accuracy in prompt handling.
