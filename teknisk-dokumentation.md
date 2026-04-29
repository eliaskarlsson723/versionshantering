# Hur skapar man ett Windows Server VM i Hyper-V

# Målgrupp: Nybörjare på Hyper-V

# Instruktioner

## 1. Öppna hypervisorn Hyper-V

## 2. Skapa två mappar i C: VM och ISO

## 3. I Hyper-V gå till Hyper-V inställningar, ändra sökvägarna till C:\VM för virtuella hårddiskar och virtuella datorer 

## 4. Ladda ner ISO-filen för Windows Server 2022, spara den i C:\ISO

## 5.	Installera VM: Åtgärd → Ny → Virtuell dator…

## 6.	Välj namn och klicka i rutan Lagra den virtuella datorn på en annan plats

## 7. Välj generation 2

## 8. Tilldela startminne: 2048 mb, använd dynamiskt minne för den här virtuella datorn ska vara ibockad

## 9. Välj en virtuell switch (default switch ger åtkomst till internet för VM) 

## 10. Skapa en virtuell hårddisk, storlek: 30GB

## 11. Välj installera ett operativsystem från en startbar avbildningsfil, välj din avbildningsfil i mappen C:\ISO

## 12. Tryck på slutför för att skapa ditt VM

## 13. Under virtuella datorer bör ditt nya VM nu synas, högerklicka och välj inställningar → kontrollpunkter och bocka ur automatiska kontrollpunkter

## 14. Du kan nu starta ditt VM för installation av OS, högerklicka → Anslut för att få upp ett fönster till din VM, därifrån kan du trycka på starta
