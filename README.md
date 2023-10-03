# TugasMPM

Tugas Metoda Pemrograman Modern

## Installation 🔨

Clone this repository and import into **Visual Code Studio**

```bash
https://github.com/TugasMPM/TugasMPM.git
```

## Configuration ⚙️

### Keystores:

Create `db.sql` with the following info:

```query
-- Table structure for table `user_alif`
CREATE TABLE `user_alif` (
  `id_alif` int(3) NOT NULL,
  `nama_alif` varchar(50) NOT NULL,
  `username_alif` varchar(50) NOT NULL,
  `password_alif` varchar(255) NOT NULL,
  `level_alif` int(1) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Dumping data for table `user_alif`

INSERT INTO `user_alif` (`id_alif`, `nama_alif`, `username_alif`, `password_alif`, `level_alif`) VALUES
(4, 'Alif', 'alifganteng', 'alifganteng123', 1),
(5, 'Nadhif', 'nadhifganteng', 'abc', 2),
(6, 'Tatang', 'tatangsutarma', 'tatanggaganteng', 3);

-- Indexes for table `user_alif`

ALTER TABLE `user_alif`
  ADD PRIMARY KEY (`id_alif`);

-- AUTO_INCREMENT for table `user_alif`

ALTER TABLE `user_alif`
  MODIFY `id_alif` int(3) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=8;
COMMIT;
```
