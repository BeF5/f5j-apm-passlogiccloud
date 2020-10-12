クライアントからの接続テスト
=========================================================

#. ブラウザからAPMのVirtulal ServerのFQDN/IPアドレスに接続します。
   
   .. image:: images/mod3-1.png
      :scale: 50%
      :align: center
   |  
#. PassLogicに登録したユーザIDを入力し、対応するドメインを選択し、:guilabel:`次へ` ボタンを押します。
   
   .. image:: images/mod3-2.png
      :scale: 55%
      :align: center
   |  
#. マス目に沿ったワンタイムパスワードを入力し、:guilabel:`ログイン` ボタンを押します。
   
   .. image:: images/mod3-3.png
      :scale: 55%
      :align: center
   |  
#. ADのユーザ名とパスワードを入力し、:guilabel:`ログオン` ボタンを押します。
   
   .. image:: images/mod3-4.png
      :scale: 60%
      :align: center
   |  
#. **F5 Networks VPNを開く** を選択します。
   
   .. image:: images/mod3-5.png
      :scale: 50%
      :align: center
   |  
#. 接続中です。
   
   .. image:: images/mod3-6.png
      :scale: 50%
      :align: center
   |  
#. SSL-VPN接続されます。
   
   .. image:: images/mod3-7.png
      :scale: 60%
      :align: center
   |  
#. Group毎のACLが反映されているか、確認をします。

   |  
#. **Access >> Overview >> Active Sessions** にて、SSL-VPN接続中のユーザ一覧が確認できます。
   
   .. image:: images/mod3-8.png
   |  
#. **Session ID** を選択すると、以下のようにセッションログが表示されます。
   
   .. image:: images/mod3-9.png
   |  
#. **Variables** のViewを押すと、以下のように各セッション変数の内容が表示されます。
   
   .. image:: images/mod3-10.png
   |  
#. その他、テストの際には、以下の ログを参照して下さい。

    - 全般的なログ： /var/log/ltm
    - APM(認証関連)のログ： /var/log/apm
    - PassLogicクラウド版のログ閲覧






