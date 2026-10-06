# D&D with LLM

Play Dungeons & Dragons using Python with the assistance of an LLM (Large Language Model), all packaged within a Docker container.

## Features

- **Text-based Gameplay** - Engage in immersive text-based adventures with the assistance of the LLM
- **Character Creation** - Create and customize your own characters for your D&D adventures
- **Dynamic Storytelling** - Experience dynamic storytelling, where the plot unfolds based on your decisions and actions
- **Dice Rolling** - Utilize dice rolling mechanics to determine the outcome of actions and encounters
- **Flexible Gameplay** - Play solo or with friends, with the LLM acting as the Dungeon Master (DM) to guide you through your adventures

## Requirements

- Docker

## Setup

1. Clone this repository:

```bash
git clone https://github.com/itsdarklikehell/dnd-with-llm.git
cd dnd-with-llm
```

2. Create a `.env` file:

```env
OPENAI_API_KEY=<your api key>
```

3. Build and run:

```bash
docker build -t dnd-with-llm .
docker run -it dnd-with-llm
```

Or using Make:

```bash
make build
make run
```

## Development

A dockerized development environment is available:

```bash
make build-dev
make run-dev
```

## License

MIT
