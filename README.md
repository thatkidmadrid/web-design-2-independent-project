# Project Plan
## Define your project
### What's the company/topic/brand?
> The topic for my independent website project is Yu-Gi-Oh! Deck profiles
### Why are you choosing this topic?
> I have recently returned to collecting and playing the card game and I can think of ways to use web design techniques to meet the requirements of the project. 
### What are the three pages? (Home, + 2 more)
> - Home
>   - Main navigation
>   - Introductory text
>   - Imagery and iconography to provide context and establish design language for the website
>   - List of featured Decks, and Cards
> - Deck List View
>   - Grid of decks
>     - Links to the Decks with descriptions
> - Detailed Deck View
>   - Grid of Cards that make up the Deck
>   - Different states for the cards if they are limited, semi-limited, banned etc.
> - Detailed Card View
>   - Recreate layout of a Yu-Gi-Oh! Trading card using a flex container
>   - Include a list of related cards
## Where will you get the content & imagery?
> I plan to use Unsplash, Creative Commons, and my own iconography and photography for the image content; I will write my own written content


---


## Content Inventory

Title | Type | URL | Images | Content | keywords
-- | -- | -- | -- | -- | --
Home | Landing page | /index.html | Banner, Deck icons, Card icons | Intro blurb, Featured Deck names, Featured Card names | Yugioh, Decks, Cards, Trading Cards
Deck List | Menu | /decks/index.html | Banner, Deck icons | Deck Names, Deck Descriptions, Deck Sizes, ,Deck Status | Decks, Yugioh
[Deck Name] Overview | Article | /decks/deck-01.html | Banner, Card Icons | Deck Name, Deck Description, Card Names | Deck, [Deck Name], Yugioh
[Card Name] Details | Details | /cards/card-01.html | Card artwork, Card-component icons, Card icons, Deck Icons | Card Name, Card Description, Related Decks and Cards | Card, [Card Name], DetailsYugioh

---

## Sitemap
```
                          ┌────────┐
                          │┼──────┼│
                          ││      ││
       ┌──────────────────┼│ HOME │┼ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─┐
       │                  ││      ││                     
       │                  │┼──────┼│                    │
       │                  └──── ───┘                     
┌──────┼──────┐                │                        │
│┼───────────┼│                                          
││           ││                │                        │
││ DECK LIST ││                                          
││           ││                │                        │
│┼───────────┼│                                          
└──────┼──────┘                │                        │
       │               ┌─────── ───────┐                 
       │               │┼─────────────┼│                │
       │               ││             ││                 
       └───────────────┼│ [DECK NAME] ││                │
                       ││             ││                 
                       │┼─────────────┼│                │
                       └───────┼───────┘                 
                               │                ┌───────┼───────┐
                               │                │┼─────────────┼│
                               │                ││             ││
                               └────────────────┼│ [CARD NAME] ││
                                                ││             ││
                                                │┼─────────────┼│
                                                └───────────────┘
```

With the links:
```
                          ┌────────┐
                          │┼──────┼│
    ┌─────┐               ││      ││
    │Decks├───────────────┼│ HOME │┼ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─┐
    └──┬──┘               ││      ││                    │
       │                  │┼──────┼│                    
       │                  └──── ───┘                    │
┌──────┼──────┐                │                       
│┼───────────┼│                                         │
││           ││  ┌─────────────┴──────────────┐         
││ DECK LIST ││  │Featured Decks > [Deck Name]│         │
││           ││  └───────────── ──────────────┘         
│┼───────────┼│                │                        │
└──────┼──────┘                                         
       │               ┌───────┼───────┐                │
       │               │┼─────────────┼│                
  ┌────┴──────┐        ││             ││  ┌─────────────┴──────────────┐
  │[Deck Name]├────────┼│ [DECK NAME] ││  │Featured Cards > [Card Name]│
  └───────────┘        ││             ││  └─────────────┬──────────────┘
                       │┼─────────────┼│                
                       └─────── ───────┘                │
                               │                ┌─────── ───────┐
                               │                │┼─────────────┼│
                         ┌─────┴─────┐          ││             ││
                         │[Card Name]├──────────┼│ [CARD NAME] ││
                         └───────────┘          ││             ││
                                                │┼─────────────┼│
                                                └───────────────┘
```
All pages will have basic navigation:
- Home
- All Decks
- All Cards (if time permits)
- Featured Decks
  - Deck 01
  - Deck 02 [disabled]
  - Deck 03 [disabled]
- Featured Cards
  - Card 01
  - Card 02 [disabled]
  - Card 03 [disabled]


---


## Wireframes

### Home
![Project Plan (1)](https://user-images.githubusercontent.com/6340290/140676059-3e400f36-9e15-4bf3-8156-95fc72f2db5a.png)
![Project Plan (2)](https://user-images.githubusercontent.com/6340290/140676086-801362c8-0be4-4a73-861f-072ab91dfb82.png)

### Deck List
![Project Plan (3)](https://user-images.githubusercontent.com/6340290/140676126-805de14d-1368-44aa-abca-cf7751a219a7.png)
![Project Plan (4)](https://user-images.githubusercontent.com/6340290/140676130-9fc91127-454a-4a6a-aabd-d08f8fb74766.png)

### Deck Details
![Project Plan (5)](https://user-images.githubusercontent.com/6340290/140676175-16322fda-c76b-48e7-8415-2b7d39514e33.png)
![Project Plan (6)](https://user-images.githubusercontent.com/6340290/140676182-dd860961-2b92-4241-a830-b8619ab4215f.png)

### Card Details
*TBD*


---


## Logo
### 256px
*TBD*
### 64px
*TBD*
### 32px
*TBD*


---


## Moodboard
![Desktop - 2 (1)](https://user-images.githubusercontent.com/6340290/140705008-f4cb41d4-0100-490c-bfa3-983ce5cfa166.png)


