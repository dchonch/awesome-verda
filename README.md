# Awesome Verda

<div align="center"><img src="https://awesome.re/badge-flat.svg" /></div>

[Verda](https://verda.com/) (formerly DataCrunch) is a European AI cloud provider from Helsinki, Finland, offering on-demand GPU instances, clusters, serverless inference, and managed endpoints — powered by 100% renewable energy.

_Please read the [contributing guidelines](contributing.md) before contributing._

## Contents

- [Official Resources](#official-resources)
- [Developer Tools](#developer-tools)
- [Guides & Tutorials](#guides--tutorials)
- [Blog Posts](#blog-posts)
  - [Architecture & Infrastructure](#architecture--infrastructure)
  - [Benchmarks & GPU Deep Dives](#benchmarks--gpu-deep-dives)
- [Customer Stories](#customer-stories)
- [Talks & Videos](#talks--videos)
- [Press & Media](#press--media)
- [Community](#community)
- [Related Projects](#related-projects)

## Official Resources

- [Verda](https://verda.com/) - Official website.
- [Documentation](https://docs.verda.com/) - Platform docs for instances, clusters, containers, storage, and networking.
- [API Reference](https://api.datacrunch.io/v1/docs) - RESTful API documentation.
- [Blog](https://verda.com/blog) - Engineering blog with benchmarks, guides, and platform updates.
- [Trust Center](https://trust.verda.com/) - Security certifications and compliance info.
- [Products & Pricing](https://verda.com/products) - GPU instances, clusters, and inference services with current pricing.
- [FAQ](https://verda.com/faq) - Frequently asked questions.

## Developer Tools

- [Python SDK](https://github.com/verda-cloud/sdk-python) - Official Python library for the Verda API. ([Docs](https://datacrunch-python.readthedocs.io/))
- [Go SDK](https://github.com/verda-cloud/verdacloud-sdk-go) - Official Go SDK for managing instances, volumes, and SSH keys.
- [Terraform Provider](https://github.com/verda-cloud/terraform-provider-verda) - Terraform and OpenTofu provider for Verda resources. ([Registry](https://registry.terraform.io/providers/verda-cloud/verda/latest))
- [Terraform Docs](https://docs.verda.com/infrastructure-as-code/terraform/) - Getting started with Terraform on Verda.
- [OpenTofu Docs](https://docs.verda.com/infrastructure-as-code/opentofu) - Using the Verda provider with OpenTofu.

## Guides & Tutorials

- [Deploy DeepSeek-R1 with SGLang and Terraform](https://verda.com/blog/deploy-deepseek-r1-with-sglang-and-terraform) - Step-by-step deployment using Terraform.
- [Deploy DeepSeek-R1 671B on 8x H200](https://verda.com/blog/deploy-deepseek-r1-on-8x-nvidia-h200) - Running a 671B parameter model on multi-GPU instances.
- [Deploy with vLLM (In-Depth)](https://docs.verda.com/containers/tutorials/deploy-with-vllm-indepth/) - Deploying LLM inference endpoints using vLLM.
- [Deploy with Replicate Cog (In-Depth)](https://docs.verda.com/containers/tutorials/deploy-with-replicate-cog-indepth) - Deploying image generation models with Cog.
- [Async Inference with Whisper](https://docs.verda.com/containers/tutorials/async-whisper) - Asynchronous speech-to-text inference tutorial.
- [Pyxis and Enroot for Instant Clusters](https://verda.com/blog/pyxis-and-enroot-integration-for-the-datacrunch-instant-clusters) - Container runtime integration for multi-node clusters.
- [Practical Deep Learning for Coders (fast.ai)](https://course20.fast.ai/start_datacrunch) - fast.ai course setup guide for Verda instances.

## Blog Posts

### Architecture & Infrastructure

- [The Verda Stack: Optimizing the AI Cloud](https://verda.com/blog/the-verda-cloud-stack-for-ai) - Deep dive into Verda's infrastructure stack.
- [Data Movement in NVIDIA's Superchip Era](https://verda.com/blog/data-movement-in-the-nvidia-gh200-grace-hopper-superchip) - MEMCPY analysis from Grace Hopper GH200.
- [Multi Data Center Training: Prime Intellect](https://verda.com/blog/multi-data-center-training-prime-intellect) - Distributed training across data centers.
- [Privacy by Architecture: Verda and ExpressVPN](https://verda.com/blog/expressai-confidential-computing) - Building confidential AI infrastructure.
- [Verda and Siili Solutions: Sovereign LLM-as-a-Service](https://verda.com/blog/verda-and-siili-solutions-launch-a-sovereign-llm-as-a-service-offering) - EU-sovereign inference endpoints.

### Benchmarks & GPU Deep Dives

- [NVIDIA GB300 NVL72: Architecture & Performance](https://verda.com/blog/gb300-nvl72-architecture) - Specs and architecture breakdown.
- [NVIDIA B300 vs. B200: Complete Comparison](https://verda.com/blog/nvidia-b300-vs-b200-complete-gpu-comparison-to-date) - Generational GPU comparison with architecture and software stack details.
- [NVFP4 Explained: Blackwell Low-Precision Floating Point](https://verda.com/blog/nvfp4-nvidia-blackwell-intro) - How NVIDIA Blackwell unlocks FP4.
- [FLUX on B200 vs H100: Real-Time Image Inference](https://verda.com/blog/flux-on-b200-vs-h100-real-time-image-inference-with-wavespeedai) - Image generation benchmark.
- [DeepSeek-V3 H200 Inference Benchmarking](https://verda.com/blog/deepseek-v3-llm-nvidia-h200-gpu-inference-benchmarking) - LLM inference performance analysis.
- [DeepSeek-V3 + SGLang: Inference Optimization](https://verda.com/blog/deepseek-v3-sglang-inference-optimization) - Serving optimization techniques.
- [Multi-Head Latent Attention in DeepSeek + SGLang](https://verda.com/blog/deepseek-sglang-multi-head-latent-attention) - MLA architecture analysis and memory efficiency benefits.
- [ClusterMAX v2 Bronze Ranking by SemiAnalysis](https://verda.com/blog/verda-formerly-datacrunch-ranked-bronze-in-clustermax-v2-by-semianalysis) - Independent cluster performance evaluation.

## Customer Stories

- [How Freepik Scaled FLUX to Millions of Requests/Day](https://verda.com/blog/how-freepik-scaled-flux-media-generation-to-millions-of-requests-per-day) - Scaling image generation with Verda and WaveSpeed.
- [How Simli Achieved Real-Time AI Avatar Inference](https://verda.com/blog/how-simli-achieved-cost-efficient-real-time-inference-for-interactive-ai) - Cost-efficient interactive AI avatars.
- [Revolutionizing Marine Mammal Research with AI](https://verda.com/blog/revolutionizing-marine-mammal-research-with-ai-powered-photo-identification) - AI-powered photo identification for conservation.

## Talks & Videos

- [Ruben Bryon at Slush 2025](https://www.youtube.com/watch?v=JD13gFxPfG8) - Verda CEO presentation at Slush.
- [Verda: First Hyperscaler from the Nordics (Nordea)](https://www.nordea.com/en/news/verda-sets-out-to-be-the-first-hyperscaler-from-the-nordics) - Nordea interview with Ruben Bryon on Verda's vision.

## Press & Media

- [Verda Raises $117M (TNW)](https://thenextweb.com/news/verda-117m-funding-lifeline-ventures-ai-cloud) - The Next Web on the funding round.
- [Verda Bets on AI Cloud (Data Center Knowledge)](https://www.datacenterknowledge.com/ai-data-centers/verda-bets-on-ai-cloud-as-workloads-fragment-across-platforms) - Industry analysis.
- [Finnish AI Cloud to Challenge AWS and Azure (Trending Topics)](https://www.trendingtopics.eu/finnish-ai-cloud-startup-verda-raises-e100m-to-challenge-aws-and-azure/) - European market positioning.
- [Verda Raises EUR 100M (Sifted)](https://sifted.eu/articles/verda-raises-e100m-to-build-european-hyperscaler) - European tech perspective.
- [Verda on Crunchbase](https://www.crunchbase.com/organization/datacrunch-io) - Company profile and funding history.

## Community

- [Community Forum](https://forum.verda.com/) - Official forum for questions and discussions.
- [Verda on gpus.io](https://gpus.io/providers/datacrunch) - GPU pricing and provider review.
- [Verda on Shadeform](https://shadeform.com/directory/clouds/verda) - Cloud provider profile with pricing comparisons.
- [Verda on GetDeploying](https://getdeploying.com/verda) - Review, pricing, and alternatives.
- [10 Best Verda Alternatives (Spheron)](https://www.spheron.network/blog/datacrunch-verda-alternatives/) - Comparison of European GPU cloud options.

## Related Projects

- [gpuhunt](https://github.com/dstackai/gpuhunt) - Open-source GPU price aggregator that includes Verda.
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput LLM serving engine.
- [SGLang](https://github.com/sgl-project/sglang) - Fast serving framework for LLMs and VLMs.
- [Deep Learning in Cloud](https://github.com/zszazi/Deep-learning-in-cloud) - Curated list of cloud GPU providers including Verda.
