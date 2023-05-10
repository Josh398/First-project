# First-project
form {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 100%;
  max-width: 600px;
  margin: 0 auto;
}

label {
  font-weight: bold;
  margin-top: 10px;
}

input,
textarea {
  padding: 10px;
  margin-top: 5px;
  border: 1px solid #ccc;
  border-radius: 3px;
  width: 100%;
  resize: vertical;
}

button[type="submit"] {
  background-color: #0066cc;
  color: #fff;
  border: none;
  border-radius: 3px;
  padding: 10px 20px;
  margin-top: 10px;
  cursor: pointer;
}

@media only screen and (min-width: 768px) {
  form {
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  label {
    flex-basis: 100%;
    margin-top: 0;
  }

  input,
  textarea {
    flex-basis: 100%;
    margin-right: 10px;
  }

  button[type="submit"] {
    flex-basis: 100%;
    margin-top: 5px;
  }
}
