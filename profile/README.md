<div align="center">

<a href="http://kamiyomu.github.io" target="_blank">
    <img src="https://raw.githubusercontent.com/KamiYomu/.github/refs/heads/main/profile/logo.png" alt="KamiYomu logo" title="KamiYomu logo" height="150"/>
</a>

</div>

# 📖 KamiYomu

**KamiYomu** is a high-performance, extensible manga manager designed for enthusiasts who demand total control. 

By leveraging a modular **Crawler Agent** architecture, KamiYomu empowers you to discover, download, reading, and archive manga from any supported source into a private, self-hosted library.

> [!NOTE]
> **Total Extensibility:** If a site isn't supported yet, you can build your own Crawler Agent in C# and integrate it instantly.

### 🚀 Core Capabilities
* **Modular Crawling:** Support for any website via community-driven **Crawler Agents**.
* **Local Archival:** Download and store high-quality images in a structured local library.
* **Private Hosting:** A built-in web reader to access your collection from any device, anywhere.
* **Developer Friendly:** Comprehensive SDK and Validator tools for building custom agents.


[![GitHub followers](https://img.shields.io/github/followers/kamiyomu)](https://github.com/orgs/KamiYomu/followers)
[![GitHub stars](https://img.shields.io/github/stars/kamiyomu/kamiyomu)](https://github.com/kamiyomu/kamiyomu/stargazers)
[![GitHub contributors](https://img.shields.io/github/contributors/kamiyomu/kamiyomu)](https://github.com/kamiyomu/kamiyomu/graphs/contributors)
[![GitHub issues](https://img.shields.io/github/issues/kamiyomu/kamiyomu)](https://github.com/kamiyomu/kamiyomu/issues)
[![GitHub License](https://img.shields.io/github/license/kamiyomu/kamiyomu)](https://github.com/kamiyomu/kamiyomu/blob/main/LICENSE.txt)



## Community

Join the conversation and be part of the KamiYomu community:

[![Join the discussion on Github](https://img.shields.io/github/discussions/kamiyomu/kamiyomu?logo=github&label=Join%20the%20community)](https://github.com/KamiYomu/KamiYomu/discussions)

## Web App

[![KamiYomu/KamiYomu - GitHub](https://github-readme-stats.vercel.app/api/pin/?username=KamiYomu&repo=KamiYomu&show_icons=true&theme=tokyonight&border_radius=8&hide_border=true&description_lines_count=3)](https://github.com/KamiYomu/KamiYomu/)

## Documentation

[![KamiYomu/KamiYomu.github.io - GitHub](https://github-readme-stats.vercel.app/api/pin/?username=KamiYomu&repo=KamiYomu.github.io&show_icons=true&theme=tokyonight&border_radius=8&hide_border=true&description_lines_count=3)](https://github.com/KamiYomu/KamiYomu.github.io)

## 🚀 Build a Crawler Agent: Empower the KamiYomu Community

The heart of **KamiYomu** is its community, and the soul of the community is access to content. By building a **Crawler Agent**, you aren't just writing code, you are building the bridges that connect readers to the stories they love.

> [!IMPORTANT]
> Your contributions help keep the platform decentralized, diverse, and accessible. Every agent you build opens up a new world for thousands of users.

### 🌟 Why Join the Mission?

* **Direct Impact:** Help users discover content from sources that aren't yet supported.
* **Developer Recognition:** Showcase your skills! Published agents on NuGet feeds (like NuGet.org) give you visibility within the ecosystem.
* **Full Autonomy:** You own your code. We provide the platform; you provide the magic.

### 🛠️ Get Started in 3 Simple Steps

We believe in "Developer Joy." You don't have to start from scratch:

1. **Clone the Template:** Use our [Sample Crawler Agent](https://github.com/KamiYomu/KamiYomu.CrawlerAgents.Sample) as your foundational reference.

[![KamiYomu/KamiYomu.CrawlerAgents.Sample - GitHub](https://github-readme-stats.vercel.app/api/pin/?username=KamiYomu&repo=KamiYomu.CrawlerAgents.Sample&show_icons=true&theme=tokyonight&border_radius=8&hide_border=true&description_lines_count=3)](https://github.com/KamiYomu/KamiYomu.CrawlerAgents.Sample)

2. **Build & Validate:** Ensure your agent is performant and platform-compliant using our built-in **Validator Tool**. The easiest way to run this is via the provided `Dockerfile`.
    * **CLI:** Run `docker build` to validate your agent in a clean environment.
    * **Visual Studio:** Set the `Dockerfile` as your startup project to trigger the validation suite automatically.
3. **Publish & Deploy:** Once validated, push your package to any NuGet feed (such as NuGet.org). **KamiYomu** will automatically detect and integrate your agent into the ecosystem.

### 🔍 Naming Convention
To ensure your crawler agent is automatically discovered by KamiYomu, follow the standard naming pattern: 
`[DeveloperName].CrawlerAgents.[TargetSite]`

**Example:** `YourName.CrawlerAgents.TheWebSite`


