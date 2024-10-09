Copyright 2024 Google, LLC. This software is provided as-is,
without warranty or representation for any use or purpose. Your
use of it is subject to your agreement with Google.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# Gemini Function Calling

This notebook provides a simple example for using Function Calling within Gemini to access data from external API's for grounding. The example shows how to get the current time and weather information using two different external API endpoints while still maintaining the ability of the model to generate additional content outside of the grounding sources.


In order to use this notebook, you will need to generate your own API key from https://www.weatherapi.com/. You can register with a free account to generate a new API key and then replace the text in the key.txt file.

For more information please visit https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/function-calling#function-parameters-bp
