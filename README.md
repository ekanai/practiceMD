practiceMD
==========
**強調**  
# 見出し  
* リスト
    * 子リスト
1. 順序リスト
2. 順序リスト２

#運用手順  
### ブランチ作成
案件対応時は必ず新規branchを作成して対応すること。  
__ブランチ命名規約__

    追加／変更案件
        feature_{機能名（英語）}
    障害
        bugfix_{障害番号}
    Thymeleaf
        Thymeleaf_{案件（画面）名}


###　リモート反映
1. 直接「master」及び「develop」ブランチへの「push」は行わないこと。  
2. developブランチへマージしたい場合は、ローカルで作成したブランチをリモートへ「push」した後に「merge request」を作成すること。request先は管理者に設定すること。