<template>
    <div>
      <table>
        <thead>
          <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Phone</th>
          </tr>
        </thead>
        <tbody>
          <!-- <tr v-for="(user) in users" :key="user.name">
            <td>{{ user.name }}</td>
            <td>{{ user.email }}</td>
            <td>{{ user.phone }}</td>
          </tr> -->
          <tr :key="dhgsvchgdsv">
            <td>John</td>
            <td>john@email</td>
            <td>9984902811</td>
          </tr>
          <tr :key="ewrtuyewa">
            <td>John</td>
            <td>john@email</td>
            <td>9984902811</td>
          </tr>
          <tr :key="csuygdsudao">
            <td>John</td>
            <td>john@email</td>
            <td>9984902811</td>
          </tr>
          <tr :key="qwioxsancen">
            <td>John</td>
            <td>john@email</td>
            <td>9984902811</td>
          </tr>
        </tbody>
      </table>
    </div>
  </template>

<script>
  export default {
    data() {
      return {
        users: [
          { name: "John Doe", email: "johndoe@example.com", phone: "555-1234" },
          { name: "Jane Smith", email: "janesmith@example.com", phone: "555-5678" },
          { name: "Bob Johnson", email: "bobjohnson@example.com", phone: "555-9012" },
        ],
      };
    },
  };
</script>
