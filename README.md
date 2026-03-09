# Lab-Power-Supply
ENG:
The laboratory power supply project was developed to support everyday work during the repair of electronic equipment as well as during the implementation of various electronic projects. The output voltage range is approximately 0 V to 18.5 V, while the maximum load current can reach up to 3 A. Regulation of these parameters is achieved using constant voltage (CV) and constant current (CC) control loops.

The system is powered by an external laptop power supply with an output voltage of 20 V. Control of the power supply functions is performed using an incremental encoder. The device offers both a manual operating mode, in which voltage and current are adjusted using potentiometers, and predefined modes with stored voltage and current settings.

To reduce power losses and limit the amount of heat generated, a switching converter is used to lower the supply voltage to an appropriate level. The voltage is then stabilized using a linear regulator with a dropout voltage of approximately 1.6 V.

To ensure effective heat dissipation, a 12 V fan is used. This voltage is obtained using a 20 V/12 V voltage regulator that is mounted directly on the heatsink to improve cooling conditions.

The 5 V logic section of the system is powered through a two-stage voltage regulation path consisting of 20 V/12 V and 12 V/5 V voltage regulators. This configuration provides a stable power supply for the control circuitry, particularly the operational amplifiers and the microcontroller.

The measurement of the actual current and voltage values is performed using two channels of the analog-to-digital converter (ADC). To convert the measured current into a corresponding voltage signal, a dedicated current sensing amplifier is used. The reference values for current and voltage are set using digital-to-analog converters (DAC) integrated in the microcontroller.

PL:
Projekt zasilacza laboratoryjnego został opracowany z myślą o wsparciu codziennej pracy podczas naprawy urządzeń elektronicznych oraz przy realizacji różnego rodzaju projektów elektronicznych. Zakres napięcia wyjściowego wynosi od około 0 V do 18,5 V, natomiast maksymalny prąd obciążenia może osiągać wartość do 3 A. Regulacja tych parametrów realizowana jest za pomocą pętli stabilizacji napięcia (CV – Constant Voltage) oraz prądu (CC – Constant Current).

Układ zasilany jest z zewnętrznego zasilacza laptopowego o napięciu 20 V. Sterowanie funkcjami zasilacza odbywa się przy użyciu enkodera inkrementalnego. Urządzenie oferuje zarówno tryb pracy manualnej, w którym regulacja napięcia i prądu odbywa się za pomocą potencjometrów, jak również tryby pracy z zapisanymi wcześniej wartościami napięcia i prądu.

W celu ograniczenia strat mocy oraz zmniejszenia ilości wydzielanego ciepła zastosowano przetwornicę impulsową, która obniża napięcie zasilania do odpowiedniego poziomu. Następnie napięcie jest stabilizowane przy użyciu stabilizatora liniowego o napięciu dropout wynoszącym około 1,6 V.

Dla zapewnienia skutecznego odprowadzania ciepła zastosowano wentylator o napięciu zasilania 12 V. Napięcie to uzyskiwane jest za pomocą stabilizatora 20 V/12 V, który został zamontowany bezpośrednio na radiatorze w celu poprawy warunków chłodzenia.

Logika układu zasilana napięciem 5 V realizowana jest poprzez dwustopniowy tor stabilizacji napięcia, składający się ze stabilizatorów 20 V/12 V oraz 12 V/5 V. W ten sposób zapewnione jest odpowiednie zasilanie dla elementów układu sterowania, w szczególności wzmacniaczy operacyjnych oraz mikrokontrolera.

Pomiar rzeczywistych wartości prądu oraz napięcia realizowany jest przy użyciu dwóch kanałów przetwornika analogowo-cyfrowego (ADC). W celu przekształcenia mierzonego prądu na odpowiadające mu napięcie zastosowano dedykowany wzmacniacz pomiarowy prądu. Zadawanie wartości prądu i napięcia odbywa się natomiast przy wykorzystaniu przetworników cyfrowo-analogowych (DAC) wbudowanych w mikrokontroler.
