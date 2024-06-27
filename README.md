# Utilizing Generative AI to Improve Health Literacy: Health Info GPT

## Overview
An AI application was developed to condense complex health information into simpler, more digestible main points, with options for further simplification and translation into other languages like Spanish. This tool will also allow users to highlight specific keywords to locate and understand relevant information efficiently.

## Background
### Description of Problem/Opportunity

Health literacy has been a rising issue among Americans for quite some time now. According to the CDC, there are two types of health literacy – personal health literacy and organizational health literacy. Personal health literacy is “the degree to which individuals can find, understand, and use information and services to inform health-related decisions and actions for themselves and others” (CDC, 2023). Organizational health literacy is “the degree to which organizations equitably enable individuals to find, understand, and use information and services to inform health-related decisions and actions for themselves and others” (CDC, 2023).

For this project, I will focus specifically on organizational health literacy. It is vital to improve organizational health literacy so people can make properly informed health decisions utilizing the correct and accurate information. Suppose people cannot understand the correct information given to them by health organizations or providers. In that case, they will make health decisions that endanger their health and their community's public health. This can be seen through the varying health decisions made during the COVID-19 pandemic. As such, it is important to ensure that information provided by health organizations is easily digestible for all audiences. 

Citations:
CDC. “What Is Health Literacy? .” Centers for Disease Control and Prevention, 11 July 2023, www.cdc.gov/healthliteracy/learn/index.html. Accessed 21 Mar. 2024. 

### Proposed Solution/Approach

Given a passage of information from a health organization, resource, or provider, the AI application created for this project will be able to condense the information into a much more readable form of the information’s main points. There will be an option to simplify the information further if necessary. Users can translate the information into another language (most likely Spanish) if they are much more comfortable with another language than English. Suppose users need the information for a specific purpose. In that case, they can input keywords highlighted in the information passage so they can easily and efficiently find the information they are looking for. 

## Project Goals 
 
### Goal 1: Condense information into simple language for increased readability
### Goal 2: Translate information into another language to increase accessibility of information
### Goal 3: Highlight keywords and only return information associated with keywords for increased and more efficient readability

## Project Metrics 

### Metric 1: Accuracy of translation

The accuracy of the English-to-Spanish translation will be tested for both the translation of the information passage and the translation of the condensed points. Does it make sense to a native speaker of the translated language? Letter grades will be determined by accuracy percentage. 0% - F, 20% - D, 50% - C, 80% - B, 90% - A

### Metric 2: Readability Score

The readability of the condensed information will be determined by the Grammarly Performance score the condensed information will receive. I have access to Grammarly Premium, which will provide additional pointers. I set the Grammarly Performance score to be based upon the following Grammarly criteria used to determine readability: Domain - General, Intent - Inform, Audience - General Knowledge (the lowest setting), Formality - Neutral. 0% - F, 20% - D, 50% - C, 80% - B, 90% - A

## Evaluation

**Goal 1: Condense information into simple language for increased readability**

My primary goal was to condense the information in health literature into simple language so the user could better understand it. The user can also ask specific questions related to them and the provided health literature to understand what pertains to them in the health literature. Regarding Metric 2 (Readability Score), most of the resulting AI-generated condensed versions of the health literature that I ran through the GPT received a letter grade of B with numerical grades in the higher 80s. The health literature I used for this project came from diverse sources, including the Centers for Disease Control and Prevention (CDC), National Institute of Health (NIH), HIV.gov, and other news media sources that people may access to conduct health decisions.

I achieved this goal, as seen from my relatively high readability scores. Reaching this goal required some tweaking to the GPT to ensure the information was conveyed yet engagingly. Initially, the information was condensed but was still condensed in a very formal tone, similar to the inputted health literature. While this simplifies the content and makes it more concise, it does not increase the readability of the content because the issue of complex language remains. As such, I let the GPT know to use simple, friendly, engaging language to convey the information from the inputted health literature. This greatly improved the Readability score from a C to a score of B, with a numerical score change of nearly 20 points (i.e. 70% to 85%+). However, as the Readability score is not yet at an A level, some tweaks could be made to improve the readability of the outputted health information. 

**Goal 2: Translate information into another language to increase accessibility of information**

My second goal was to translate the information into another language to increase its accessibility. I decided to have the GPT translate the health information into Spanish because Spanish is one of the most commonly spoken languages in the United States. As such, it is important to have readable health literature in Spanish so that Spanish speakers can also make informed health decisions. Initially, I ran into some issues with the GPT not being able to properly translate all of the health-related languages, so I uploaded an English-Spanish Dictionary for Health-related words to ensure that the GPT translated the health words to the best of its abilities. As I do not speak Spanish fluently, I surveyed people fluent in Spanish on their impressions of the readability of the simplified Spanish language. Most people could understand the information but found some small grammar and spelling errors in the passage. As a result, this GPT scores a low B in the Readability score (Metric 2). However, tweaks could still be made to improve the GPT’s Spanish readability score, particularly through improving the grammar and spelling of the outputted words. 

**Goal 3: Highlight keywords and only return information associated with keywords for increased and more efficient readability**

This goal was harder to achieve and received a Readability score of a low C. The GPT was able to highlight keywords but could not relay the highlighted keywords or information in a way that relayed the information in a more simplified manner. There is still a lot of room for improvement to reach this goal. In a way, I was able to make the GPT give me information based on keywords inputted by the readable user so I could achieve half of this goal. However, I could not make the GPT highlight or keywords in a way that makes it easier for the user to understand the information. The GPT would only highlight important words, which does not help people understand what they should know. For example, if given the sentence “You should get a vaccine”, the GPT would return “You should get a **vaccine**.” If someone is looking for the highlighted keywords and were not reading the entire passage, they would only look at the word “vaccine”. This is not helpful for the readability of the passage. Trying to achieve this goal made me realize that the key to using this GPT would be for the user to ask or input keywords and information that pertains to them – which made me change the intentions of this GPT. 

## Link to GPT Assistant
https://chat.openai.com/g/g-W9u1migFl-health-info-helper

## Tools Used
- OpenAI GPT Builder, OpenAI Actions, OpenAI Knowledge Base

