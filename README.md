function WriteComponent(name, surname, username, img) {
    return `
 <div class="col-3">
    <div class="card">
        <button id=${username} onclick="DeleteUser(${username})" id="delete" class="btn btn-danger position-absolute end-0 top-0 m-2 rounded-3">
            <i class="fa-solid fa-trash"></i>
        </button>
        <img src=${img} class="card-img card-img-top" alt="...">
        <div class="card-body">
            <h5 class="card-title">${name} ${surname}</h5>
            <p class="card-text mb-1 link-primary">@${username}</p>
        </div>
    </div>
</div>
    `
}

