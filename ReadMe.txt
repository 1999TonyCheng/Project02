[V]add efmodels
===
�|���t��
[v] add ���U�|���\��
 add Models/Infra/HashUtility.cs
 add AppSettings,<add key = "salt" value="ar!Zu@#$D691RR"/>
 add Models/VewModels/RegisterVm.css
 add RegisterExts class,�X�R��kToEFModel(RegisterVm)
 add Controllers/MembersController
  add Register action(Get,Post)
  add Views/Members/Register.cshtml,RegisterConfirm.cshtml
  modify _Layout.cshtml,add Register link

[v]��@�s�|��email�T�{�\��
	�|���ҥΪ�url:/Members/ActiveRegister?memberId=99&confirmCode=tttttttttt
	modify MembersController
		add ActiveRegister(memberId,confirmCode)
	add Views/Members/ActiveRegister.cshtml

[V]��@ �n�J/�n�X����
	�u���b�K���T�ӥB�w�����}�q���|���~���\�n�J�A��@���e�A�Х��ӧO�إߤ@�Ӥw/���}�q���|�������A��K����
	modify web.config, add Authenthcation node
	add Models/ViewModels/LoginVm.cs
	modify MembersController, 
		add Login action(Get,Post)
		add Logout action(get only)
	modify _layout�A�[�Jlogin/logout link
	����:�ثe�b�S�n�J�ɡA�|�۰ʧP�_�v���A�L�k�˵�About page; �n�J/�n�X�\��w��{

[working on]��@ �ק�ӤH�򥻸��-�إ߷|�����߭�
	add Models/ViewModels/EditProfileVm.cs
	add Models/ViewModels/MemberExts class ,�X�R��k

	modify MembersController
		add Index action �|�����߭�,�b�n�J���\����|�ɦV����
			add Index view page
		add EditProfile
[]�oconfirm email���s���U�|��
