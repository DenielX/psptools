PSPCipher��һ��PRX��������ͬ���е�pspdecrypt.prx���������ȫ��6.20 mesg_led_02g.prx�����򹤳̶����ģ�ͬ6.20�̼��Ľ��ܳ��򼸺���ȫһ������������˵�ܱ�ʹ��pspdecrypt.prx��edecrypt��prxdecrypter��isotool�ǽ��ܸ��������prx��

ʹ�÷�����
��Ҫ���ܵ�PRX���浽ms0:/ENC/EBOOT.BIN������������Զ����ܵ�ms0:/DEC/EBOOT.BIN ��

��ǰ�汾: 0.0

Ŀǰֻ�����˺�Сһ���ֵ�key, (0xd91613f0, 0xd91612f0, 0x2e5e10f0, 0x2e5e12f0)����ΪĿǰֻ�Ǽ�����֤�׶Ρ�Ȼ����ע��Ŀǰ��PSPCipher��û�б�Ľ������ܽ���0x2e5e10f0 PRX�����key����������������Ϸ������Ҳ����˵��������ϵͳ��������Ϸ�����ˡ��������£���������1.01����Ϊ����

PBOOT.PBP��unpack-pbp��ѹ��ɵø�DATA.PSP��PARAM.SF0��ǰ���Ǹ���0x2E5E10F0���ܵ�EBOOT.BIN���ǲ�����������򣬺����ǲ��������Ϸ��Ϣ�ļ�����������Ϸ�汾��Ϣ��

��DATA.PSP������EBOOT.BIN������PSPCipher���ܡ���PARAM.SF0һ����wqsg_umd�滻ԭISO���EBOOT.BIN(�������������˹ģ������EBOOT.OLD)��PARAM.SF0�����滻ʱ��ע��Ҫ�����ƽ⡣�滻������Ϸ�ϰ����ǿ���Ϣ�Ϳ��Կ��������Ϸ�����°汾��

�Ѿ���God Eater 1.01��ż���ʦsp�����ϳɹ�������μ�http://bbs.a9vg.com/read.php?tid=1477236&fpage=1

====================================================================================================================================

PSPCipher by liquidzigong@a9vg.com(aka hrimfaxi)

It can decrypt PRX type 5 (0x2e5e12f0) when prxdecrypter 2.4 etc failed to handle. It's a completely reimplemention version as mesg_led_02g.prx and memlmd_02g.prx from FW 6.20. So if you are clever to find DRM decryption key you can decrypt DRMed module with it.

The sample decrypts host0:/enc/EBOOT.BIN and save to host0:/dec/EBOOT.BIN. kbridge dir contains decryption implemention. Please see pspcipher.h to use the code.

The source is covered by GPLv3 to fight aginst Sony NPDRM.