# ai-law-newsletter
Automates a monthly AI &amp; Law newsletter. Uses ScaleSerp for research and OpenAI for summaries, formats results into Markdown, and runs on GitHub Actions with output sent to Zapier for automatic posting to Substack.

This project automates the creation of a monthly newsletter covering recent developments at the intersection of artificial intelligence and the law. It fetches fresh articles, case studies, and regulatory updates via the ScaleSerp API, filters for relevance, and uses OpenAI’s GPT models to generate summaries and polish the final text.

The newsletter is formatted in Markdown, saved as an output file, and scheduled to run automatically each month through GitHub Actions. The output can then be delivered to Substack subscribers using Zapier, ensuring timely, consistent updates without manual work.

🔑 API keys (OpenAI, ScaleSerp) are stored securely in GitHub Secrets to keep sensitive information safe.
