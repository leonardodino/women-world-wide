# Women World Wide Dev 🗺👩🏾‍💻👩🏿‍💻👩🏻‍💻👩🏽‍💻👩🏼‍💻

[WomenWorldWide.dev](https://WomenWorldWide.dev) is a map of coding and tech groups around the world around the world for all who identify as women. 

This map represents just a tiny sliver of the great organizations that share this focus. 

If you know of a local group that should be on the map, please submit a pull request, so that we can be sure to add it!

## Running the repo locally
If you'd like to submit a pull request, you can run the project locally:

```
git clone git@github.com:prisma/women-world-wide.git
cd women-world-wide
yarn 
yarn develop
```

## Contributions 🤝
We are actively seeking to add additional organizations for the map. To add your group, please add each of the organization's locations as a separate JSON file in the [`src/data/orgs`](./src/data/orgs) directory. 

You can see an example below (using the *Women Who Code Atlanta* organization):

```
{
  "image": "https://pbs.twimg.com/profile_images/1016008941757718528/tCnG03WW_400x400.jpg",
  "name": "Women Who Code Atlanta",
  "country": "usa",
  "city": "atlanta",
  "topics": ["Tech"],
  "mainLink": "https://www.meetup.com/Women-Who-Code-Atlanta/",
  "secondaryLinks": [
    {
      "name": "Twitter",
      "url": "https://twitter.com/wwcatl"
    },
    {
      "name": "Slack",
      "url": "https://wwcatl.typeform.com/to/WKy2an"
    }
  ]
}
```

A submitted organization should have the following: 
* Filename: The filename should be the organization name followed by the group's location. For example: `women-who-code-atlanta.json`
* `image`: A link to the organization's image 
* `name`: The name of the organization (including the branch location)
* `country`
* `city`: *If your local organization branch just has a country, but not a city, this section can be skipped*
* `topics`: If the group focuses on a specfic technology, you can add more details about the language or focus here 
* `mainLink`: This is the main link where your organization lives. Often this is a meetup link, but it could be the group's homepage, or any other place where readers can get additional information 
* `secondaryLink`: These are additional links that correspond to an organization — for example if the group has a specific twitter, etc 

## Maintenance 💪
If you see an inactive (without activity for over six months) organization on this map, please open up an issue, so that the map can remain as current and helpful as possible. 




Made with ❤️ by [Prisma](prisma.io)
