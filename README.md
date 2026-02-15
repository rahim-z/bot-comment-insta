for termux:
  "install l bot"
git clone https://github.com/rahim-z/bot-comment-insta

  "open lbot"
cd bot-comment-insta

  "Install Required Packeges & Libraries"
bash setup.sh

  "get insta post id"
./get_post_id.sh

  "last cmd"
./send_comment.sh
