### 1 Initialize Nextjs - npx create-next-app@latest
## 2 Intialize shadcn - npx shadcn-ui@latest init
## 3 Install necessary libraries and dependencies like shadcn input, form etc
## Nextjs routing and file folder structure. 
### Create proper routing groups and routes of nextjs
# --> In the app directory, nested folders are normally mapped to URL paths. However, you can mark a folder as a Route Group to prevent the folder from being included in the route's URL path.

# This allows you to organize your route segments and project files into logical groups without affecting the URL path structure.

# Route groups are useful for: Organizing routes into groups e.g. by site section, intent, or team.
# Enabling nested layouts in the same route segment level:
# Creating multiple nested layouts in the same segment, including multiple root  #    layouts
# Adding a layout to a subset of routes in a common segment

## Create proper pages layouts. 
# A page is UI that is unique to a route. You can define a page by default exporting a component from a page.js file.

# For example, to create your index page, add the page.js file inside the app directory

# A layout is UI that is shared between multiple routes. On navigation, layouts preserve state, remain interactive, and do not re-render. Layouts can also be nested.

# You can define a layout by default exporting a React component from a layout.js file. The component should accept a children prop that will be populated with a child layout (if it exists) or a page during rendering.

#  For example, the layout will be shared with the /dashboard and /dashboard/settings

### Start clerk authentication
## Install and mount clerk in the app with Clreak provider
# Create a middleware.ts and copy the middleware code from clerk docs
# Test clerk sign up and sign in

## Create sidebar component, use shadcn Button component, Install it and then render the sidebar in root's layout

## Create a MobileNav, use shadcn sheet component, Install it and then render the sidebar in root's layout

## Connect mongodb 