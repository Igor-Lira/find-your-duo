# Find Your Duo

<img width="400px" src="FindYourDuo-min.PNG" alt="exemplo imagem">

        video demo: https://www.youtube.com/embed/gfqAo8Os1XI
 
## Description

        This full-stack application helps gamers to find other people to play
        together according to their preferences, such as which game they play,
        when they usually are online, and if they use voice chat. The user can
        also create an announcement and wait for others to connect.
        
        Both mobile and web versions have three main pages: a game list, an
        announcement list and a formulary to create an announcement.

## About

        On the server side, NodeJs with Express is used to create a server and
        perform Create and Read commands for Game and Announcement models. I
        used Prisma TypeScript ORM since it facilitates data modelling
        and migrations with safety typing and auto-completion. Not only that, but
        Prisma has an interface that helps to interact with the currently stored
        data. I defined the schemas based on my needs: 1 game has
        n announcements, and 1 announcement is related to 1 game.
        
        On the client side, I used React to build components such as the Game
        Card and the Announcement Card, and React Native to create the mobile
        version. Aditionally, Tailwind CSS was used for styling the website.
