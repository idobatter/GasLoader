# GasLoader
## What's GasLoade?
- Google Apps Script�p��Script Loader�ł��B
- Google Docs�܂��͌��J���ꂽ�T�[�o��ɂ���javascript�t�@�C����ǂݍ����GAS���ŗ��p�ł���悤�ɂ��܂��B

## �g����
### �T�[�o�[��ɂ���t�@�C����ǂݍ��ޏꍇ
  
  GasLoader.require("https://raw.github.com/soundTricker/gasmarty-jarty_for_google_apps_script/master/src/jarty.js",null , 0);
  
  - ������ url
  - ������ charset �����R�[�h
  - ��O���� cacheSecond �X�N���v�g���L���b�V�����鎞�� 0�̏ꍇ�̓L���b�V������܂���B �����w�肵�Ȃ��ƃf�t�H���g�l�ŃL���b�V������܂��B

### Google Docs����t�@�C����ǂݍ��ޏꍇ

   GasLoader.requireFromDocs({key}  , 0);

  - ������ key Google Docs��key
  - ������ cacheSecond �X�N���v�g���L���b�V�����鎞�� 0�̏ꍇ�̓L���b�V������܂���B�����w�肵�Ȃ��ƃf�t�H���g�l�ŃL���b�V������܂��B

### �L���b�V�����ꂽ�t�@�C�����폜����B

   GasLoader.removeCache({key});
  - ������ key Google Docs��key �܂���url
  
## ����
- �O���X�N���v�g��ǂނ̂ŃZ�L�����e�B�ɋC�����Ă��������B
- �O������ǂݍ��񂾃t�@�C������Spreadsheet�Ȃǂ̔F�؂��K�v��API�ւ̈ˑ��֌W������ꍇ�A�Ăяo�����œ���API���Ă�łȂ��ƁA�F�؃_�C�A���O���ł܂���B

## ��肽���Ȃ�
- �񓯊��Ŏ���Ă����悤�ɂ���������API�Ȃ���B�B�B

