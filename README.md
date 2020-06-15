# ESP-CAM

ESP-CAM �ǻ���ESP_WHO������һ���沿����ʶ��ƽ̨��ʹ��Espressif Systems��ESP32оƬ��

# ����
ESP32-CAM�ǰ��ſɷ���С�ߴ������ͷģ�顣��ģ�������Ϊ��Сϵͳ�����������ߴ��Ϊ27*40.5*4.5mm��
ESP32-CAM�ɹ㷺Ӧ���ڸ������������ϣ������ڼ�ͥ�����豸����ҵ���߿��ơ����߼�ء�����ʶ���Լ�����������Ӧ�ã���������Ӧ�õ�������������
ESP32-CAM����DIP��װ��ֱ�Ӳ��ϵװ弴��ʹ�ã�ʵ�ֲ�Ʒ�Ŀ���������Ϊ�ͻ��ṩ�߿ɿ��Ե����ӷ�ʽ������Ӧ���ڸ���������Ӳ���ն˳��ϡ�
�����С��802.11b/g/n Wi-Fi + BT/BLE SoCģ�顣

![ ��Ʒ](img / CAM5.jpg)

��ESP_CAM�У�������SDcrad��uart��SNTP��smartconfig�ȹ��ܣ��ṩ�˿��ٿ��������������˹�����֤�����ٿ������ڡ�

* **��������ģ��** �ṩ��SDcrad��uart��SNTP��smartconfig����.

* **��Ƶ�����������** ͨ������ͷ�����룬��Ƶ��ͨ��http�������������http�����ṩ�˲ٿ�����ͷ�ӿ�.

* **�������ʶ��** ͨ��http����Ŀ��ƹ��ܼ��ɿ����������ʶ��Ĺ���.**ע��:ESP_CAM����ֱ��ʿ�ͨ��http�������������ʶ������ʱֻ֧��320*240�ķֱ���**.

* **ͼ�����㱣��** �ڲ�ͬurl�ӿڿ�ʵ��ͼ��������뱣�棬�����ַΪPC��.


# ��������

## Ӳ��׼��

* ESP_CAMģ�鿪����
* ����ģ�飨USB-TTL��
* �Ű���
* PC
* Ӳ������:
![ uart](img / cam_uart.jpg)

## �������
### �����
* ʹ�ð��ſɿ���������[��ΰ�װ���ſ�һ�廯��������](https://docs.ai-thinker.com/ai_ide_install)��[���ʹ�ð��ſ� ESP ϵ��һ�廯��������](https://docs.ai-thinker.com/ai_ide_use)��[���Ϊ ESP ϵ��ģ����¼�̼�](https://docs.ai-thinker.com/esp_download)
* �Լ��������https://esp-idf.readthedocs.io/zh_CN/latest/get-started/index.html 
* ESP_CAM SDK���أ�esp-idfʹ��V4.0.0����

# SDkĿ¼���

## Components

�����SDK����Ҫ��ܣ��ڲ�����һЩ����������㷨

## Camera

������������ESP32������豸����������

## esp-face

��ESP�����������API�������磬�������������ʶ��Ŀ�ܡ�

# Examples
ʾ���ļ��а�����ʾAPI���ܵ�ʾ��Ӧ�ó���

����ʾ����
1. ����ʾ������ `esp_cam\examples\single_chip\camera_web_server`.
```
cd esp_cam\examples\single_chip\camera_web_server
```

2. ���մ���ģ����ߣ����벢ˢ����Ŀ
```
make build
make flash -p [PORT]
```
3. �߼��û�����ʹ�������޸�ĳЩѡ�� `make menuconfig`.

4. ���봮��ģ�������£���Linux�����򿪼����,Ҳ��win���������ֱ�Ӵ򿪴�������
```
make monitor
```
5. ʹ���ֻ�����smartconfig���������ֻ�����wifi����£���������

6. �����ɹ���PC�����������Ϊģ������ip���ɼ�ص�����ͷ����

���ÿ��ʾ����README.md���Ի�ȡ������ϸ��Ϣ��


# Resources

* [Check the Issues section on github](https://github.com/espressif/esp-who/issues) if you find a bug or have a feature request, please check existing Issues before opening a new one.

* If you're interested in contributing to ESP-CAM, please check the [Contributions Guide](https://esp-idf.readthedocs.io/en/latest/contribute/index.html).
