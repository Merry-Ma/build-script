build-script
============

ǰ�˴���淶��飬js��cssѹ����cssԤ����������

----------

ǰ�˲���Ӧʹ��ͳһ�����ã������õ��޸�Ӧ���ύ����

## ��װ ##

1. ��װ[nodejs](http://nodejs.org/download/),��װ�������Ҫ��������
1. ����װԴ����Ϊ�й��������������� `npm config set registry http://registry.cnpmjs.org/ --global`
1. ���������� `npm install -g grunt-cli`
1. ��ѹ [grunt.rar](grunt.rar?raw=true) ����Ŀ��Ŀ¼
1. ��Ŀ��Ŀ¼���������� `npm run build`

������װֻ��ִ�������������

## ʹ�� ##

1. ��Ŀ��Ŀ¼��������`grunt`
1. �޸��ļ���`/js/src/*.js`��`/css/src/*less`)���ļ����Զ���������ļ���Ȼ����������Զ�ˢ��
1. git�ύ�ļ�ʱ���������޸ĵĴ��룬��������Ĵ��뽫�޷��ύ
1. ����'grunt dev'�������ر��������ļ�
1. ����'grunt publish'�����������ĵ�(documentation/development/frontend/jsdoc/)����ѹ��ǰ���ļ�(assets/js,assets/css)

## �������� ##

- ������Զ�ˢ�²�����ص�ַ
	- [Chrome](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei)
	- [Safari](http://download.livereload.com/2.0.9/LiveReload-2.0.9.safariextz)
	- [Firefox](http://download.livereload.com/2.0.8/LiveReload-2.0.8.xpi)
- lessԴ��λ����ʾ������ص�ַ
	- [Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/firecompass-for-firebug/)

## ���� ##

- [JSHint�����ĵ�](https://github.com/Tours4Fun/documentation/blob/master/development/frontend/jshint_config.md)