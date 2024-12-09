# bitcointranscripts-media

Archive for supporting media content (images, slides, diagrams) for [bitcointranscripts](https://github.com/bitcointranscripts/bitcointranscripts)

## Repository Structure
This repository mirrors the directory structure of [bitcointranscripts](https://github.com/bitcointranscripts/bitcointranscripts) to align media files with their corresponding transcripts.

Here is an example of the directory structure for media files associated with the transcript at [`bitcoin-core-dev-tech/2019-06/2019-06-05-wallet-architecture.md`](https://github.com/bitcointranscripts/bitcointranscripts/blob/master/bitcoin-core-dev-tech/2019-06/2019-06-05-wallet-architecture.md):

```
└── bitcoin-core-dev-tech
    ├── 2019-06
        ├── 2019-06-05-wallet-architecture
            ├── 2019-06-05-wallet-architecture.jpg
            ├── slides.pdf
            └── flow-example.jpg
```

## Usage
When adding media files:
1. Follow the same path structure as the transcript
2. Use descriptive filenames that clearly indicate the content



## Linking Media in Transcripts
To reference media files in your transcripts, use the following format:

```markdown
![Description](https://raw.githubusercontent.com/bitcointranscripts/media/master/bitcoin-core-dev-tech/2019-06/2019-06-05-wallet-architecture/2019-06-05-wallet-architecture.jpg)
```

Make sure to:
- Use the raw GitHub URL (raw.githubusercontent.com)
- Include the full path from the repository root
- Add a meaningful description for accessibility

