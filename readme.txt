1. hostsファイルのansible_portとsite_nameを環境や好みに合わせて書き換える。
   ansible_portは自分のvmの22番ポートに繋がっているポートを選択、site_nameは何でもいい。
2. ansible-playbook -i hosts main.yaml --ask-become-passを実行。(hostsのansible_user=rootなら--ask-become-passは不要)
