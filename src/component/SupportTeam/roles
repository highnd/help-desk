import React, { Component } from "react";
import roles, { id, name } from "./mockdata/roles";

class Role extends Component {
  state = {};
  constructor(props) {
    super(props);
  }

  getRoleById(id) {
    return (
      <span>
        {" "}
        {
          roles.find(function(element) {
            return element.id == id;
          }).name
        }
      </span>
    );
  }
  render() {
    return this.getRoleById(this.props.id);
  }
}

export default Role;
