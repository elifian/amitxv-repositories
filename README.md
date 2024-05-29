# MeasureSleep
Allows you to measure the slept

Позволяет замерить slept

<image src="Pictures/MeasureSleep.jpg">

# SetTimerResolution
A utility that allows you to configure timer resolution, set the value you specifically need
arguments: SetTimerResolution.exe --resolution 5000 --no-console

Утилита, позволяющая настроить timer resolution, установить конкретно нужное вам значение
аргументы: SetTimerResolution.exe --resolution 5000 --no-console

# MicroAdjustBenchmark
Allows you to determine which hpet you need (the minimum value in the graph)
.ps1 script should be located next to SetTimerResolution and MeasureSleep

Позволяет определить какой вам нужен hpet (минимальное значение в графике)
.ps1 скрипт должен находится рядом с SetTimerResolution и MeasureSleep
https://chart-studio.plotly.com/create/#/

<image src="Pictures/MicroAdjustBenchmark.png">

# ReservedCpuSets
Prevents scheduled interrupts and tasks on reserved cores

Предотвращает запланированные прерывания и задачи на зарезервированных ядрах

<image src="Pictures/ReservedCpuSets.jpg">

# AutoCpuAffinity
Allows you to check which kernel produces the best performance

Позволяет вам проверить, какое ядро обеспечивает наилучшую производительность

<image src="Pictures/AutoGpuAffinity.jpg">

# SCEWIN
SCEWIN is a tool to modify BIOS NVRAM variables including options that are not visible through UEFI. As far as I know, it is exclusively shipped with MSI Center. This repository was created to provide the SCEWIN binaries without installing the MSI bloatware so that you don't have to

Это инструмент для изменения переменных NVRAM BIOS, включая параметры, которые не видны через UEFI. Насколько я знаю, он поставляется исключительно с MSI Center. Этот репозиторий был создан для предоставления готовых двоичных файлов без установки вредоносного ПО MSI, так что вам не придется этого делать

### USAGE
Run the Export.bat script to export NVRAM setting values to nvram.txt
Run the Import.bat script to write the configuration in nvram.txt to NVRAM
Запустите скрипт Export.bat, чтобы экспортировать значения настроек NVRAM в nvram.txt
Запустите скрипт Import.bat, чтобы записать конфигурацию в nvram.txt в NVRAM

# MouseTester
Forms a curve by which you can view the accuracy of the mouse

Формирует кривую, по которой можно посмотреть точность мыши

<image src="Pictures/MouseTester.jpg">
