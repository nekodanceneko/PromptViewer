========================================
PromptViewer�ɂ���
========================================
StableDiffusion�ō쐬�����摜�̃v�����v�g�����m�F���Ȃ���A�w��t�H���_�ւ̐U�蕪����
�ȈՂɍs���̂�ړI�Ƃ����c�[���ƂȂ�܂��B

�udocs/PromptViewer-image.jpg�v���Q��


========================================
�C���X�g�[�����@
========================================
�C���X�g�[���t�H���_��C:\tool\git\PromptViewer�Ƃ����ꍇ�Ő����B
Python�̓C���X�g�[������Ă�����̂Ƃ��܂��B

1)C:\tool\git\PromptViewer���쐬
2)�ȉ��̃t�@�C�����i�[����
  PromptViewer.py
  PromptViewer_beep.wav
  PromptViewer_filecansel.wav
  PromptViewer_filecopyok.wav
  PromptViewer_filemoveok.wav
  PromptViewer_moveend.wav
  PromptViewer_movetop.wav
  pvsubfunc.py
  
  PromptViewer_settings.json    ��1
  
3)�R�}���h�v�����v�g�𗧂��グ�Ĉȉ������s����B���̎菇�̓C���X�g�[���̈�x�̂�
  3-1)�J�����g�t�H���_�̈ړ��ړ�
    c:
    cd C:\tool\git\PromptViewer
  3-2)venv�����쐬�Aactivate����
    py -m venv venv
    .\venv\Scripts\activate.bat
  3-3)���p���郉�C�u�������C���X�g�[������
    pip install PyQt5 pyperclip Image
  3-4)����m�F
    py PromptViewer.py
    ������OK

4)�N���ɕ֗��ȃV���[�g�J�b�g�̍쐬
  �K���ȃt�H���_�ŉE�N���b�N���āu�V�K�쐬�v->�u�V���[�g�J�b�g�v
  ���ڂ̏ꏊ�Ɉȉ������
  C:\tool\git\PromptViewer\Scripts\pythonw.exe C:\tool\git\PromptViewer\PromptViewer.py
  
  ����̓V���[�g�J�b�g���_�u���N���b�N�ŃA�v���̂悤�Ɏg���܂�

��1:�ݒ�t�@�C���͂Ȃ���Ύ����ō쐬�����̂łȂ��Ă��ǂ�


========================================
�ݒ�t�@�C���ɂ���
========================================
PromptViewer_settings.json�Ɉȉ��̏���ێ����Ă��܂��B
! ----------------------------------------
! ����image-fcopy-dir�Aimage-fmove-dir�́y�����̊��ɍ��킹�ĕK���z���������Ă�������
! ----------------------------------------

image-fcopy-dir   W,��L�[�ɂ��t�@�C���̃R�s�[��t�H���_��
image-fmove-dir   S,���L�[�ɂ��t�@�C���̃��[�u��t�H���_���i������̓t�@�C���̈ړ��ƂȂ�̂Œ��Ӂj

info-label-w      Prompt�\���̈�̉���(�f�t�H���g�l:480)
geometry-x,y      �Ō�̃E�C���h�E�\���ʒu
geometry-w,h      �Ō�̃E�C���h�E�\���T�C�Y

�ȉ��͌��ʉ��ƂȂ�܂��iWAVE�t�@�C���ōD���Ȃ��̂ɕύX�\�ł��A���Ԃ�j
sound-beep        �������s���̃G���[�I��
sound-fcopy-ok    �R�s�[�������̉�
sound-fmove-ok    ���[�u�������̉�
sound-f-cansel    �R�s�[�A���[�u�̃L�����Z�����̉�
sound-move-top    ���̉摜�\�����ɁA���肵�čŏ��̉摜�ɖ߂������̉�
sound-move-end    �O�̉摜�\�����ɁA���肵�čŌ�̉摜�ɖ߂������̉�


========================================
���p���@
========================================
�A�v����ɉ摜�t�@�C���iJPG��PNG�t�@�C���j�A�������͉摜�t�@�C�����������t�H���_��
�h���b�O���h���b�v���Ă�������

--------
�L�[����
�i������ς������l�̓\�[�X�̃L�[�C�x���g�������D���ɏ��������Ă��������j
--------
AD,���E   �����t�H���_���̑O��̉摜�Ɉړ�
Q,ESC     �I��
0,1,2     �摜�̃T�C�Y��0:1/2�A1:���{�A2:2�{�Ƀt�B�b�g�\���i�g�O������j
F,Enter   �S��ʕ\���ɐ؂�ւ��i�g�O������j
W,��      �ݒ�t�@�C����image-fcopy-dir�Ŏw�肳�ꂽ�t�H���_�ɕ\���摜���R�s�[ ��2
S,��      �ݒ�t�@�C����image-fmove-dir�Ŏw�肳�ꂽ�t�H���_�ɕ\���摜�����[�u ��3
K         �V�[�h�ԍ����R�s�[�o�b�t�@��
P         Prompt��������R�s�[�o�b�t�@��
N         Negative Prompt��������R�s�[�o�b�t�@��
H         Hires Prompt��������R�s�[�o�b�t�@��

--------
�}�E�X����
--------
�z�C�[������      �����t�H���_���̑O��̉摜�Ɉړ�
�E�N���b�N        �ݒ�t�@�C����image-fcopy-dir�Ŏw�肳�ꂽ�t�H���_�ɕ\���摜���R�s�[
���_�u���N���b�N  �S��ʕ\���؂�ւ��i�g�O������j
���h���b�O        �E�C���h�E���ړ�

��2:�R�s�[�͍ēx�L�[���������ƂŃL�����Z���i�R�s�[�悩��폜�j�o���܂�
��3:���[�u�͍ēx�L�[���������ƂŎ������o���܂��i�摜����ړ����Ă��Ȃ��ꍇ�̂݉\�j


�ȏ�
