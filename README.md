# willpatera.com

Personal website [willpatera.com](http://willpatera.com).

## Setup

After cloning the repository, create a virtual environment using `virtualenv`. 

```bash
virtualenv -p python3.6 env
```

Activate the virtual environment (instructions for fish shell users).

```bash
source env/activate.fish
```

Install requirements.

```bash
pip install -r requirements.txt 
```

## Development

Build and serve with `ivy`

```fish
ivy build
ivy serve
```

## Deployment

more here soon...