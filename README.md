# DALL·E QA Testing Report  

## Overview  
This project documents a **manual QA testing analysis** of OpenAI’s DALL·E image generation model. The focus was on evaluating **accuracy, prompt adherence, visual consistency, and brand/logo misinterpretation issues.** The goal was to identify defects in AI-generated outputs and recommend improvements.

## Testing Approach  
- **Exploratory Testing:** Prompting DALL·E with structured and unstructured requests to assess behavior.  
- **Scenario-Based Testing:** Evaluating how well the model adheres to specific instructions, including object placement, style, and composition.  
- **Defect Logging:** Identifying and categorizing recurring issues with severity levels and suggested fixes.  

## Key Findings  
- AI **frequently ignores prompt details**, leading to incorrect visual elements.  
- **Hallucinated objects** appear in images that were not part of the request.  
- **Text rendering failures** prevent AI from correctly displaying readable text in images.  
- **Inconsistent output** when repeating the same prompt, reducing predictability.  
- **Brand and context misinterpretation** results in unnecessary logo insertions when requesting an image for a platform.  

## Project Contents  
- **QA_Report.md** – Detailed defect report with findings and recommendations.  
- **Test_Cases.md** – Structured test cases for evaluating DALL·E output accuracy.  
- **Bug_Tracking_Log.md** – Logged defects with severity levels and descriptions.  

## How to Use  
1. **Review `QA_Report.md`** for the primary findings.  
2. **Check `Test_Cases.md`** to see structured test execution steps.  
3. **Use `Bug_Tracking_Log.md`** to explore identified issues.  

## Future Work  
- Expanding test coverage to **multi-character compositions and spatial logic.**  
- Developing a **repeatability test suite** to assess prompt consistency.  
- Exploring **bias detection** in AI-generated imagery.  

## Contributors  
Martin Krizan

## License  
MIT  
