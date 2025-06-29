# What's New in Generative AI for Beginners .NET

This page tracks the history of new features, tools, and models added to the course. Check back for updates!

## June 2025

### New: Azure OpenAI Sora Video Generation Demo

- **New Lesson 3 Sample: Azure Sora Video Generation**
- Lesson 3 now features a hands-on demo showing how to generate videos from text prompts using the new [Sora video generation model](https://learn.microsoft.com/azure/ai-services/openai/concepts/video-generation) in Azure OpenAI.
- The sample demonstrates how to:
  - Submit a video generation job with a creative prompt.
  - Poll for job status and download the resulting video file automatically.
  - Save the generated video to your desktop for easy viewing.
- See the official docs: [Azure OpenAI Sora video generation](https://learn.microsoft.com/azure/ai-services/openai/concepts/video-generation)
- Find the sample in [Lesson 3: Core Generative AI Techniques /src/VideoGeneration-AzureSora-01/Program.cs](../03-CoreGenerativeAITechniques/src/VideoGeneration-AzureSora-01/Program.cs)

### New eShopLite Scenario: Concurrent Agent Orchestration (June 2025)

- **New Scenario: Concurrent Agent Orchestration**
- The [eShopLite repository](https://github.com/Azure-Samples/eShopLite/tree/main/scenarios/07-AgentsConcurrent) now features a scenario demonstrating concurrent agent orchestration using Semantic Kernel.
- This scenario showcases how multiple agents can work in parallel to analyze user queries and provide valuable insights for future analysis.

## May 2025

### Azure OpenAI Image Generation Model: gpt-image-1

- **New Lesson 3 Sample: Azure OpenAI Image Generation**
  - Lesson 3 now includes code samples and explanations for using the new Azure OpenAI image generation model: `gpt-image-1`.
  - Learn how to generate images using the latest Azure OpenAI capabilities directly from .NET.
  - See the [official Azure OpenAI DALL·E documentation](https://learn.microsoft.com/azure/ai-services/openai/how-to/dall-e?tabs=gpt-image-1) and [openai-dotnet image generation guide](https://github.com/openai/openai-dotnet?tab=readme-ov-file#how-to-generate-images) for more details.
  - Find the sample in [Lesson 3: Core Generative AI Techniques](../03-CoreGenerativeAITechniques/).

## March 2025

### MCP Library Integration

- **Model Context Protocol for .NET**: We've added support for the [MCP C# SDK](https://github.com/modelcontextprotocol/csharp-sdk), which provides a standardized way to communicate with AI models across different providers.
- This integration enables more consistent interactions with models while reducing provider lock-in.
- Check out our new samples demonstrating MCP integration in the [Core Generative AI Techniques](../03-CoreGenerativeAITechniques/) section.

### eShopLite Scenarios Repository

- **New eShopLite Repository**: All eShopLite scenarios are now available in a single repository: [https://aka.ms/eshoplite/repo](https://aka.ms/eshoplite/repo)
- The new repo includes:
  - Product catalog browsing
  - Shopping cart management
  - Order placement and tracking
  - User authentication and profiles
  - Integration with Generative AI for recommendations and chat
  - Admin dashboard for product and order management
