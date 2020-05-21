# Ruby on Rails Getting Started

#### Basics
A controller's purpose is to receive specific requests for the application. Routing decides which controller receives which requests. Often, there is more than one route to each controller, and different routes can be served by different actions. Each action's purpose is to collect information to provide it to a view.

A view's purpose is to display this information in a human readable format. An important distinction to make is that it is the controller, not the view, where information is collected. The view should just display that information. By default, view templates are written in a language called eRuby (Embedded Ruby) which is processed by the request cycle in Rails before being sent to the user.

#### Prerequisites
- Ruby
- SQLite3
- Node.js
- Yarn

#### The following were done:
1. Bootstrapped: `rails new .`
2. Generated a controller: `rails generate controller Welcome index`
3. Launch the server: `rails server`
4. Navigate to `http://localhost:3000` in your browser