# The-Real-Purdue-Menu

Gives you information on the current week's food and items.

## The Problem

I want to solve the issue of needing to look at everything in the app manually to see which item has which ingredient or its nutritional value. I also want to solve the issue of not being able to look at the entire week's food to find what fits your requirements and where it is from. 

## How It Works

- Extracts the data through an API
- Converts data into objects
- Puts that data into a CSV file
- Asks for either a name or tags
- Outputs the Item and its nutritional information or a list of Items
[link text]([https://url.com](https://lucid.app/lucidchart/e2c9d576-c7a0-4892-b5f6-e2b0c5f47438/edit?viewport_loc=-333%2C61%2C1451%2C847%2C0_0&invitationId=inv_758c136a-5372-4f98-be6f-7646049416a9))
![System diagram](docs/diagram.png)

## Tech Stack

- **Language:** Java
- **Libraries:** HttpClient, Jackson, Apache Commons CSV
- **External tools:** API.

## Setup

Step-by-step: how does someone who just cloned your repo get it
running?

```bash
git clone https://github.com/you/your-project
cd your-project
./install.sh   # or whatever
```

## Usage

How to actually run the thing, with examples.

```bash
./backup.sh ~/Documents
```

## Roadmap

Features you haven't built yet but plan to (pull these from your
"Schedule" quadrant in the Eisenhower Matrix).

- [ ] Recommendation based on location
- [ ] When the dining halls are closed
- [ ] Track nutrition based on selected meals

## Author

Ivan Yang,[ ](https://github.com/ivan04252008-lab)
