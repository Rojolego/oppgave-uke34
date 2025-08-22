* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  color: #333;
  line-height: 1.6;
}

/* Header */
header {
  background-color: #4a90e2;
  color: white;
  text-align: center;
  padding: 30px 20px;
}

/* Profil */
.profile {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  gap: 20px;
  background-color: white;

*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f5f5f5;
  color: #333;
  line-height: 1.6;
}

/* Header */
header {
  background-color: #4a90e2;
  color: white;
  text-align: center;
  padding: 30px 20px;
}

/* Hovedinnhold */
main {
  max-width: 900px;
  margin: 20px auto;
  padding: 20px;
}

.profile {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  gap: 20px;
  background-color: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.profile img {
  width: 250px;
  border-radius: 10px;
}

.profile .info {
  flex: 1;
}

/* Seksjoner i info */
.profile .info h2 {
  margin-top: 10px;
  color: #4a90e2;
}

.profile .info p {
  margin-bottom: 10px;
}

/* Footer */
footer {
  text-align: center;
  background-color: #4a90e2;
  color: white;
  padding: 15px;
  margin-top: 20px;
}

/* Responsivt for små skjermer */
@media (max-width: 600px) {
  .profile {
    flex-direction: column;
    align-items: center;
  }

  .profile img {
    width: 80%;
  }
}