# Swop

**Swop** Swop is an app for swopping stuff. It's like Tinder but for people trying to get rid of their stuff.

## User Stories

Swop's **required** functionality is completed:

- [ ] users have profiles
- [ ] users post photos of items
- [ ] each item has it's own page
- [ ] search view- "hot" "popular" "new"

Swop's **optional** features are implemented:

- [ ] tagging
- [ ] in app chat maybe
- [ ] log in using oauth
- [ ] tindr matchy swap thing

Swop's **additional** features are implemented:

- [ ] create events/meetups

## API's

Swop will use these API's

## Data Definitions

**User**

| UserId | UserName | UserPswd |
|--------|----------|-----------------|

**Profile**

| UserId | FirstName | LastName | Email | Campus | Age | PhoneNumber |
|--------|----------|-----------------|-----------|---|---|----------|

**Item**

| ItemId | ItemName | ItemDescription | ItemImage | ItemStatus | CategoryId |
|--------|----------|-----------------|-----------|------------|------------|

**Inventory**

| InventoryId | ItemId |
|--------|----------|

**"Swopping Cart"**

| SwoppingCartId | Item1 | Item2 | Status |
|--------|----------|-----------------|-----------|

**Wishlist**

| UserId | ItemId |
|--------|----------|

**Category**

| CategoryId | CategoryName | CategoryDescription |
|--------|----------|-----------------|

**Chat**

| ChatId | UserId |
|--------|----------|

**Message**

| MessageId | UserId | ChatId |
|--------|----------|-----------------|

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://beforeitsnews.com/contributor/upload/486248/images/cat-funny-5.jpg' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Notes about Swop.

## License

    Copyright [2016] [eye-OS]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
