# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# <%= form_with scope: :article, url: articles_path, local: true do |f| %>


# #     <% if @article.errors.any? %> 
# #   <h2>The following errors prevented the article from being saved</h2> 
# #   <ul> 
# #     <% @article.errors.full_messages.each do |msg| %> 
# #       <li><%= msg %></li> 
# #     <% end %> 
# #   </ul>
# #     <% end %>


# #     <p>
# #         <%= f.label :title %> <br>
# #         <%= f.text_field :title %>
# #     </p>

# #     <p>
# #         <%= f.label :description %> <br>
# #         <%= f.text_area :description %>
# #     </p>

# #     <p>
# #         <%= f.submit %>
# #     </p>

# # <% end %>
