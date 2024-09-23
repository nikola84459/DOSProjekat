Ovaj projekat ima za cilj da na osnovu slika sa magnetne rezonance glave prepozna da li je prisutan tumor na mozgu.

Prvo se pristupa obradi slike kako bi klasifikacija bila uspešna:

  Prvo se učitavaju slike iz foldera i prikazuju se
  Nakon toga se računa SNR indeks nivoa šuma na slici, gde se grafički prikazuje nivo šuma na slikama
  Nakon toga se vrši interpolacija slike primenom BICUBIC algoritma za skaliranje slike
  Posle toga se vrši uklanjanje šuma sa slika gde je SNR indeks manji od 1
  I nakong toga se pristupa segmentaciji slike kako bi se više istakao deo slike gde se nalazi tumor i kako bi klasifikacija bila uspešnija
  
Nakon toga kreira se neuronska mreža koja će se koristiti u klasifikaciji i vrši se obučavanje.

Procenat tačnost(accuracy) je na kraju obučavanja 88.57
