# ObjectTypeConvetExtentions�Ƃ� #

�I�u�W�F�N�g�^����e��^�ւ̕ϊ��p�g�����\�b�h�ł��B

# �C���X�g�[�� #

NUget���g���ĉ������B
ID��ObjectTypeConvertExtentions�ł��B

# �g���� #

## �ȒP�Ȏg�p�� ##

�擾�������^���̃��\�b�h�Ō^��ϊ����܂��B

    object str = "1";
    int ret = str.Int(); //1 as int

null��DBNull��0�ɕϊ����܂��B

    object str = null;
    int ret = str.Int(); //0 as int

null�̂܂܎擾����ꍇ�͌^��Null�̃��\�b�h���g���Ă��������B

    object str = null;
    int? ret = str.IntNull(); //null

## �Ή����Ă���^ ##

* bool
* byte
* datetime
* decimal
* double
* int
* int16
* int64
* string
* uint
