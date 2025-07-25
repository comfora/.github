# Welcome to Comfora?

> [!NOTE]
> You have found both our organization README and our root source for the [comfora.org](https://comfora.org) website?

We've open-sourced our root website source for,

- 👥 Community Engagement and Governance on our website.
- 🔎 Find something wrong? You can make a pull request!
- ✂️ A good documentation template use for other Comfora Projects.
  > We use [mkdocs-material](https://squidfunk.github.io/mkdocs-material/), shh...
- Frankly, we just ❤️ open-source.

## Contributing to Comfora

> [!WARNING]
> All contributing policies will be changed in a future organization update to be one policy instead of each project having different policies.

We love to accept your contributions to Comfora's website! Please remember these policies when contributing.

- 🇺🇸 Only English[^1] *for now*
- Don't overuse emojis! While our branding is very emoji-heavy, please don't overuse it!

Now we're ready!

### Setting up the Environment

> [!NOTE]
> If you only want to contribute to the Organization README, go ahead with editing our README in `.profile`.

- 🐍 Python 3.8 or greater
- *Optional* vscode with the following extensions installed
  - `markdownlint` by David Anson
  - `Code Spell Checker` by Street Side Software

#### Setting up the Environment - `uv` method

This is our recommended method as the package won't be installed into your python installation and is a one command only.

1. Setup [`uv`](https://docs.astral.sh/uv/getting-started/installation/) for your specific operating system.
   1. This allows you to not bother with `.venv`s and global python installations.
2. Clone the directory by doing, `git clone https://github.com/comfora/.github.git` and open code within the directory.
3. Now run `uv tool run --with mkdocs-material --with material-plausible-plugin mkdocs serve` in your terminal.
4. Now you're set for writing pages!

#### Setting up the Environment - `pip` method

> [!WARNING]
> We only have a `requirements.txt` which is maintained by Comfora Renovate for Cloudflare Workers deployments which is how we publish [comfora.org.](https://comfora.org)

Clone the directory by doing, `git clone https://github.com/comfora/.github.git` and open code within the directory.

**For Windows systems,**

1. Create a virtual environment `python -m venv venv` in the cloned directory.
2. Activate the virtual environment by `.\venv\Scripts\activate`.
3. Install the dependencies by `pip install -r requirements.txt`.

**For Linux or Unix (macOS) systems,**

1. Create a virtual environment `python3 -m venv venv` in the cloned directory.
2. Activate the virtual environment by `source venv/Scripts/activate`.
3. Install the dependencies by `pip install -r requirements.txt`.

Now you're set for writing pages!

## Licensing

All Comfora open-source projects are licensed under the **MIT License,** including this one.

- MIT License [within the repository.](LICENSE)
- Learn more about the MIT License at the [Choose a License website.](https://choosealicense.com/licenses/mit/)

[^1]: Future plans are in place and as of currently *(July 25, 2025)* we are testing localization solutions for other languages.
