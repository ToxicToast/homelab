# TODO List


- [ ] HTTP REST Endpoints with NestJs
    - [ ] Inventory
        - [ ] Category
        - [ ] Item
        - [ ] Location
        - [ ] Company
        - [ ] Type
        - [ ] Size
    - [ ] Shopping List
        - [ ] Stock (Stock that will soon run out, or that already run out)
        - [ ] Recipes (Get Recipes from REWE and attach them to the last Shopping List -> Only Works with Rewe for now)
    - [ ] Authentication
        - [ ] Register (or no Registration, they could be added via Database directly)
        - [ ] Login (returns JWT Token)
        - [ ] Me (returns encoded JWT Token Data)
    - [ ] Twitch
        - [ ] Channel (Followers)
        - [ ] Viewer (How long did a Viewer watched my Channel, what Messages did he send and whats his fav. message)
        - [ ] Stream (Last Stream, Streamtitle, Stream Game)
        - [ ] Messages (Messages send in Channel)
        - [ ] Games (Games streamed)

- [ ] Set Permissions for Endpoints
- [ ] Fix Docker Image Versioning (Latest should be replaced with the Github Tag)
- [ ] Create ArgoCD Project for Azkaban (Gateway)
- [ ] Create Pulumi Project