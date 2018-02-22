# slack-theme
Personal slack theme

// Custom Slack Styling
document.addEventListener('DOMContentLoaded', function() {
 $.ajax({
   url: 'https://cdn.rawgit.com/premonday/slack-theme/master/slack-theme.css',
   success: function(css) {
     $("<style></style>").appendTo('head').html(css);
   }
 });
});
