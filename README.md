# USC X 24 US Election Twitter/X Dataset

This repository contains multiple directories named `part_{part_number}`, where each part consists of chunk files prefixed with the timeline. Each chunk file contains 50,000 tweets related to the US election.

## Repository Structure

```
usc-x-24-us-election/
├── part_1/
│   ├── timeline_chunk_1.csv.gz
│   ├── timeline_chunk_2.csv.gz
│   └── ...
├── part_2/
│   ├── timeline_2_chunk_21.csv.gz
│   ├── timeline_2_chunk_22.csv.gz
│   └── ...
├── part_3/
│   ├── timeline_3_chunk_41.csv.gz
│   ├── timeline_3_chunk_42.csv.gz
│   └── ...
└── ...
```

## Cloning the Repository

To clone this repository, use the following command in your terminal:

```bash
git clone https://github.com/sinking8/usc-x-24-us-election.git
```

This will create a local copy of the repository on your machine.

## Data Description

- Each directory `part_{part_number}` contains chunk files that are prefixed with the timeline name.
- Each chunk file consists of **50,000 tweets** related to the US election, allowing for extensive data analysis and processing.

## Usage

You can navigate to the relevant part directory and read the chunk files for further analysis. The structure allows you to process tweets in manageable chunks, facilitating easier handling of large datasets.

## License

This repository is licensed under [MIT License](LICENSE).

